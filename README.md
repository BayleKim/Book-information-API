# Book-information-API

How to use?
You can use AJAX to call this API and will receive book information in return. If you are using jQuery, you can use the $.ajax() function in the code snippet below to get started.

$.ajax({
  url: 'https://www.cato.top:9912/...',    // "https://www.cato.top:9912/"is the address of my personal cloud server.
  dataType: 'json',
  success: function(data) {
    console.log(data);
  }
});

Results
The application will provide you with a JSON object that you can parse and apply to your application.

You can specify the format you want the results in using the format parameter.
{
  "data": [
    {
      "author":"xxx",
      "create_time":"xxx",
      "id":"xxx",
      "name":"xxx",
      "price": "xxx",
      "state": "xxx",
      "update_time": "xxx",
      "user_id":"xxx"
     }
   ]}

