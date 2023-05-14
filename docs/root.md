# 
![img](assets/hierarchy.svg)
#

The image you see above is the basic diagram of contents and its hierarchy.
The following is the rough metadata for the each sub-type (non-abstract class).

# 3. TXT

## 3.1 Blogs
### 3.1.1 Index
Loren ipsum color motor dotor signet
```json
{
    // ..
    "1_260323_171543" : {
        
        // ..
        "id" : "",
        "title" : "",
        "summary" : "",
        "category" : ""     // engineering, fiction, hypothesis, etc.

        // ..
        "metadata" : {
            "update_date" : "",        // last updated > creation time on blogs index
            "update_time" : "",        // last updated > creation time on blogs index
            "readtime_s" : 0,
            "authors" : ["<name>", "<name>", ... ]
        },

        // ..
        "data" : {
            "cover_image" : "",
            "gallery_images" : []
        }
    }
}
```

### 3.1.2 Post
Loren ipsum color motor dotor signet
```json
{
    "content" : {
        "title" : "",
        "subtitle": "",
        "preface" : "",         // usually 200 word context builder given alongide title image ON blog post
        "summary" : "",         // concise summary 50-75 word that is used in highlights or gallery
        "epilogue": "",         // optional post finisher or conclusion giver
        "data" : "path",        // actual path to the raw .md file that contains blog contents
        "tags" : [],            // related metadata / tags to this post (used more for SEO)
        "category" : ""         // post category        
    },

    "data" : {
        "images" : {
            "cover" : "path",
            "title" : "path",
            "gallery" : []
        },

        "audio" : {
            "readout" : "path"
        }
    },

    "authors" : [
        {
            "name" : "",
            "info" : "",
            "photo" : "",
            "social" : "[platform-name](url)"
        }
        
        // ...
    ],

    "metadata" : {
        "create_date" : "DD-MM-YYYY",
        "create_time" : "HH:MM UTC",
        "update_data" : "DD-MM-YYYY",
        "update_time" : "HH:MM UTC",

        "word_count" : 0,
        "readtime_s" : 0
    }
}
```

#
## 3.2 Projects
### 3.2.1 Index
```json
```

### 3.2.2 Post
```json
```