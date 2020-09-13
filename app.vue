new Vue({
el: '#app',
data: {
name: 'avinash.io'
},
filter: {
Upper(value) {
return value.toUpperCase();
}
}
});
<div id app="app">
<span>{{name | Upper}}</span>
</div>
