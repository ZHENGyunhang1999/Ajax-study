<template>
   <div class="container">
    <div class="row thumbnail center col-sm-12">
        <div class="col-sm-12">
            <h1 class="text-center" style="margin-bottom: 30px">订单详情</h1>
        </div>

        <div class="col-sm-12 ">
           <table>
               <tr>
                   <th>订单编号：</th><td>123-131-4234-1314-131</td>
               </tr>
               <tr>
                   <th>订单状态：</th><td>未付款</td>
               </tr>
               <tr>
                   <th>收货人姓名：</th><td>侯龙超</td>
               </tr>
               <tr>
                   <th>收货人地址：</th><td>内蒙古科技大学</td>
               </tr>
               <tr>
                   <th>收货人电话：</th><td>12345678901</td>
               </tr>
           </table>
        </div>
        <div class="col-sm-12">
            <table class="table table-striped table-condensed">
                <tr>
                    <th>书名</th>
                    <th>单价</th>
                    <th>数量</th>
                    <th>小计</th>
                </tr>
                <tr>
                    <td>书名</td>
                    <td>单价</td>
                    <td>数量</td>
                    <td>小计</td>
                </tr>
                <tr>
                    <td>书名</td>
                    <td>单价</td>
                    <td>数量</td>
                    <td>小计</td>
                </tr>
                <tr>
                    <td>书名</td>
                    <td>单价</td>
                    <td>数量</td>
                    <td>小计</td>
                </tr>
                <tr></tr>
            </table>
        </div>

        <div class="col-sm-12 ">
            <table>
                <tr>
                   <th> </th><th></th> <th>商品总数：</th><td>12</td> <th>订单总价：</th><td><span class="text-danger">123.0元</span></td>
                </tr>
            </table>
        </div>
    </div>
    <div></div>
    <div class="col-sm-offset-7 col-sm-5" style="padding: 30px;">
        <div class="col-sm-6 btn btn-success btn-block">继续购物</div>
        <div class="col-sm-6  btn btn-success btn-block">提交订单</div>
    </div>
</div>
</template>

<script>
export default {
   name:'OrderInfo'
}
</script>

<style scoped>
.row{
            margin-left: 20px;
            margin-right: 20px;;
        }
        .line-center{
            line-height:50px;
            text-align: center;
        }
        .row input{
            width: 50px;
        }
        .list-group-item:hover{
            background: #27ae60;

        }
        .list-group-item div:first-child:hover{

            cursor: pointer;
        }
        th{
            text-align: right;
            width: 200px;;
        }
        td{
            text-align: left;
            padding: 10px;
        }
        .table th{
            text-align: center;
        }
        .table td{
            text-align: center;
        }
</style>