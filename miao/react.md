# React
## The library for web and native user inerfaces

[==learn react==](https://react.dev/learn)   [==api Reference==](https://react.dev/reference/react)

# Create user interfaces from components
React lets you build user interfaces out of individual pieces called components. Create your own React components like **Thumbnail,** **LikeButton**, and **Video**. Then combine them into entire screens, pages, and apps.

### Video.js
```jsx
function Video({ video }) {
  return (
    <div>
      <Thumbnail video={video} />
      <a href={video.url}>
        <h3>{video.title}</h3>
        <p>{video.description}</p>
      </a>
      <LikeButton video={video} />
    </div>
  );
}