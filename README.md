# Video Generator : Create content effortlessly.

The rise of superficial content is a growing concern in our digital world. To highlight the issue, I embarked on a project to demonstrate that it's shockingly simple to replicate content that lacks depth or substance, yet manages to retain attention.

In this project, I'm specifically using [Reddit](https://www.reddit.com/) but since this kind of content is used in every other social media (Tiktok, Youtube shorts, Instagram reels...) even with their particularities the same logic can be aplied on those as well.

## Explanation :

[Praw](https://praw.readthedocs.io/en/stable/index.html) is a Python Reddit API Wrapper, so instead of using a request we can get what we want by simply using a method;
[Selenium](https://www.selenium.dev/documentation/) is an automated test tool used to provide screenshots (Firefox was best suited for this purpose, but feel free to use whatever browser you want);
And to concatenate all things together we use [MoviePy.](https://zulko.github.io/moviepy/#)

## Instructions :

- Install dependencies
- Make a copy of *config.example.ini* and rename to *config.ini*
- Register with [Reddit](https://www.reddit.com/prefs/apps/) to create an application and copy the credentials
- Use those credentials to update *config.ini* (lines 19, 20 and 21)

Now, you can run `python main.py` to be prompted for which post to choose. Alternatively,
you can run `python main.py <reddit-post-id>` to create a video for a specific post.

# Video Output :