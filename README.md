# date3
jquery时间轴(将用户活动信息以时间轴的形式显示出来)
引入time.css、jquery-3.0.0.min.js、time.js、jquery.dotdotdot.js等文件
将数据格式写成以下形式：
var jsonArr = [
        {time:'09:00',value:'访问A页面'},
        {time:'09:30',value:'访问B页面 '},
        {time:'09:50',value:'登录'},
        {time:'10:00',value:'退出'},
        {time:'10:10',value:'登录'},
        {time:'10:20',value:'退出'},
        {time:'10:50',value:'访问B页面'},
        {time:'10:50',value:'访问B页面'},
        {time:'10:50',value:'访问B页面'}
    ];
    然后调用:
    timeAxis(jsonArr);

