


## Documentation

[Intersection Observer API](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API)




## Image Uploading Status Show in Reactjs

```javascript
    const handleImage = (e) => {
        const file = e.target.files[0];
        setInputImage(file);
        const fileReader = new FileReader();
        fileReader.onload = function (e) {
        //   console.log(e.target.result);
          setImage(e.target.result);
        };
        fileReader.readAsDataURL(file);
      };
```

