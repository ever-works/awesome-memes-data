## Dataset Overview

This dataset comprises the top 980 posts from Reddit's r/memes subreddit, gathered using the PRAW (Python Reddit API Wrapper). Each entry includes an image file and a corresponding metadata record.

## Contents
- **images/**: Folder with 918 image files (formats: .jpg, .jpeg, .png, .gif) representing the meme posts.
- **metadata.json**: JSON file containing metadata for each meme post, with fields such as:
  - `id`: Reddit post ID
  - `title`: Post title
  - `selftext`: Text content (if any)
  - `url`: Direct link to the image/content
  - `permalink`: Relative Reddit URL
  - `created_utc`: Unix timestamp of post creation
  - `author`: Username of the poster
  - `subreddit`: Always "memes"
  - `score`, `ups`, `downs`: Vote counts
  - `upvote_ratio`: Proportion of upvotes
  - `num_comments`: Number of comments
  - `total_awards_received`: Count of Reddit awards
  - `is_video`: Boolean indicating video posts
  - `over_18`: NSFW flag
  - `spoiler`: Spoiler flag
  - `stickied`: Whether post is stickied
  - `locked`: Whether comments are locked
  - `distinguished`: Moderator/admin status
  - `link_flair_text`: Post flair text
  - `author_flair_text`: Author flair text
  - `thumbnail`: Thumbnail URL
  - `post_hint`: Post hint (usually "image")
  - `file_name`: Local filename matching an image in the images/ folder

## Usage Ideas
- Meme content analysis combining image and text data
- Training machine learning models for meme generation or classification
- Natural language processing on meme titles and comments
- Computer vision tasks such as image categorization or similarity search
- Multimodal research integrating visual and textual features

## License

This dataset is released under the MIT License.

## Update Frequency

Not expected to be updated (static snapshot).
