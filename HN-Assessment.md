# HackerNews Assessment

We're going to rebuild Hacker News! We will be relying on the public API here: https://github.com/HackerNews/API to do it. If you want to see what Hacker News looks like currently you can find it here: https://news.ycombinator.com/.

You will need to build this in React, focussing on how you can break things down into small components. Try to use functional components with hooks whenever you can. We have included some core functionality in the following user stories, as well as some stretch goals if you get finished early.

## User Story 1

As a Hacker News enthusiast I want to see the top 25 posts on Hacker News right now so that I can see what's new in the software world.

### Acceptance Criteria

1. When I load the app, I should see the top 25 posts, in descending order, from the Top list on Hacker News.
2. For each post I can also see the following:
   1. The post's title
   2. A link to the article
   3. The post's score
   4. The username who submitted the post
   5. When it was posted

## User Story 2

As a Hacker News enthusiast I want to see the comments for each Hacker News post so I can see the conversation going on about the subject.

### Acceptance Criteria

1. For each post I can click a button to view it's comments on a separate page. For this story you can focus on only showing a post's direct comments (not any of it's comments' nested comments, for that see User Story 5)
2. For each comment I can see the following:
   1. The comment text
   2. The user that posted the comment
   3. When the comment was posted

## User Story 3

As a Hacker News enthusiast I want to also see all of the New posts to Hacker News as well as the Top posts from the day.

### Acceptance Criteria

1. In addition to viewing the Best list, I can navigate to pages where I can view the top 25 posts in descending order from the New and Top lists on Hacker News as well.

# Stretch Goals

## User Story 4

As an uber Hacker news enthusiast, I want to not only see the top 25 posts for each list, but also the next 25 posts, and then the next 25 posts and so on.

### Acceptance Criteria

1. When viewing a list of posts, I can also navigate beyond the first 'page' of 25 posts.

## User Story 5

As an uber Hacker News enthusiast, I want to view the entire comment tree for a post so that I can view the entire discussion going on around an topic.

### Acceptance Criteria

1. When viewing the comments of a post, show not only the direct comments, but also show all of a comments' nested comments, and so on. (Hint: you will need recusion to do this)
