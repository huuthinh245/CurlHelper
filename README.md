# CurlHelper
Example 
```
axios.interceptors.request.use(req => {
  try{
    const curl = new CurlHelper(req)
    console.log(curl.generateCommand())
  }catch(er) {

  }finally {
    return req
  }
})
```
