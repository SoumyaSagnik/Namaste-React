React can be added using CDN as well. (Content Delivery Network)

```javascript
<script crossorigin src="https://unpkg.com/react@18/umd/react.development.js"></script>
<script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
```

The first tag is react, the second is react-dom. React-dom is like a bridge between browser and react. There are two separate files.

<p>Reason: react native will use something else and not react-dom. But react will be used in both places.</p>
