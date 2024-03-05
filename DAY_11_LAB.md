# Skeleton

```javascript
// TestPostModel.js
const Post = require("./Post");
const RequestHandler = require("./RequestHandler");

// Excution
lab11();

// Function Declaration
async function lab11(){
    // Given params
    const userId = 1;
    const postId = 5;

    // Create RequestHandler object

    // const post = ...
    // const allPost = ...
}
```

```javascript
// Post.js
class Post {
}
module.exports = Post;
```

```javascript
// RequestHandler.js
class RequestHandler {

    async printTargetPost(userId, postId) {
        // Construct the returned data as a Post data model from class Post
    }

    async printAllPosts(userId) {
        // Construct the returned data as a [ Post data model ] from class Post
    }

    async _getAllPosts(userId) {
    }
}
module.exports = RequestHandler;
```