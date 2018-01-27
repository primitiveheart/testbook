# datatable的自己一些理解和demo

1. datatables需要的[jquery-datatable-min.js](https://cdn.datatables.net/1.10.16/js/jquery.dataTables.min.js)和[jquery-datatable-min.css](https://cdn.datatables.net/1.10.16/css/jquery.dataTables.min.css)

2. datatables中options一些参数

| options | 解释 |
| :--- | :--- |
| serverSide | 该参数说明开启服务端，意思是在数据源来自服务端（如：ajax的形式） |
| pageLength | 该参数是每页分页的大小，默认值是10 |
| language | 表示国际化，可以使用url进行加载，如language：{url:"chinese.json"}, 里面的参数有：sLengthMenu：表示是每页大小的长度的列表，sInfo:表示是的分页框中的信息，“sSearch”：表示的搜索框，“sZeroRecords”:表示加载或搜索时没有数据时，要返回的信息，“sInfoEmpty”：表示表格没有数据，返回的信息，“oPaginate”:表示分页条的信息，这四个就是分页条中的信息，sFirst ：表示是首页，sPrevious：表示是前一页，sNext: 表示是后一页，sLast:表示是尾页。 |
| columns |  |
| columnDefs |  |
| fnDrawCallback |  |
| ajax |  |
| processing |  |
| pagine |  |
| lengthChange |  |
| searching |  |
| bInfo |  |



3. datatable的路由发送与返回的一些参数

  a. 发送请求中的携带参数 
  draw ： 
  start : 
  length:

  b. 响应返回携带的参数  
  draw:  
  recordsTotal:  
  recordsFiltered:



