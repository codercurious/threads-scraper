# Meta threads scraper ✅ FREE ✅
Interested in using this scraper? Get it here: [Meta threads scraper ✅ FREE ✅](https://apify.com/curious_coder/threads-scraper)
## Threads scraper

This scraper helps you to scrape posts by a threads user

Here is the sample output of this actor:

```json
{
	"id": "3141737961795561608_314216",
	"reply_count": "27068",
	"user": {
		"profile_pic_url": "https://scontent.cdninstagram.com/v/t51.2885-19/357376107_1330597350674698_8884059223384672080_n.jpg?stp=dst-jpg_s150x150&_nc_ht=scontent.cdninstagram.com&_nc_cat=1&_nc_ohc=euIj8dtTGIkAX-vea85&edm=APs17CUBAAAA&ccb=7-5&oh=00_AfCOXYuDeJ_OxBW9ZYSdlTfCIXdP9NBqDoMVS5rk39mEHA&oe=64ACDDC0&_nc_sid=10d13b",
		"username": "zuck",
		"id": null,
		"is_verified": true,
		"pk": "314216"
	},
	"image_versions2": {
		"candidates": []
	},
	"original_width": 612,
	"original_height": 612,
	"video_versions": [],
	"carousel_media": null,
	"carousel_media_count": null,
	"pk": "3141737961795561608",
	"has_audio": null,
	"text_post_app_info": {
		"link_preview_attachment": null,
		"share_info": {
			"quoted_post": null,
			"reposted_post": null
		},
		"reply_to_author": null,
		"is_post_unavailable": false
	},
	"caption": {
		"text": "70 million sign ups on Threads as of this morning. Way beyond our expectations."
	},
	"taken_at": 1688744372,
	"like_count": 146411,
	"code": "CuZsgfWLyiI",
	"media_overlay_info": null
}

```

## Documentation for JSON Data

The given JSON data represents an threads post with various associated attributes. Below is a breakdown of the individual components and their descriptions:

## Main Object

- **id**: The unique identifier for the post.
  - *Type*: String
  - *Example*: "3141737961795561608_314216"

- **reply_count**: The total number of replies for this post.
  - *Type*: String
  - *Example*: "27068"

- **user**: The user who created the post. This contains several sub-fields:
  - **profile_pic_url**: The URL of the user's profile picture.
    - *Example*: A direct link to the image.
  - **username**: The username of the user.
    - *Example*: "zuck"
  - **id**: The unique identifier for the user. (Can be null)
  - **is_verified**: A boolean value indicating if the user is verified.
  - **pk**: A unique key representing the user.
    - *Type*: String
    - *Example*: "314216"

- **image_versions2**: An object that lists image versions available for the post.
  - **candidates**: An array containing different image versions. 

- **original_width**: The original width of the image or video.
  - *Type*: Integer
  - *Example*: 612

- **original_height**: The original height of the image or video.
  - *Type*: Integer
  - *Example*: 612

- **video_versions**: An array containing different versions of the video (if the post is a video). 

- **carousel_media**: Represents carousel media if the post contains multiple images or videos. 

- **carousel_media_count**: The total number of media items in a carousel post. 

- **pk**: Another unique key for the post.
  - *Type*: String
  - *Example*: "3141737961795561608"

- **has_audio**: A boolean value indicating if the post (video) has audio. 

- **text_post_app_info**: Contains information related to the text of the post.
  - **link_preview_attachment**: Any link preview attached to the post. 
  - **share_info**: Information related to post sharing.
    - **quoted_post**: If the post quotes another post. 
    - **reposted_post**: If the post is a repost from another user. 
  - **reply_to_author**: Represents a reply to the post author. 
  - **is_post_unavailable**: A boolean indicating if the post is unavailable.

- **caption**: Contains the caption of the post.
  - **text**: The text content of the caption.
    - *Example*: "70 million sign ups on Threads as of this morning. Way beyond our expectations."

- **taken_at**: A timestamp indicating when the post was created (in Unix time format and can be converted to a human-readable date and time format.)
  - *Type*: Integer
  - *Example*: 1688744372

- **like_count**: The total number of likes for the post.
  - *Type*: Integer
  - *Example*: 146411

- **code**: A unique code associated with the post.
  - *Type*: String
  - *Example*: "CuZsgfWLyiI"

- **media_overlay_info**: Contains information related to any media overlays on the post. 
