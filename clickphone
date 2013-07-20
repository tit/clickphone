(function () {
  var a, span, phone;
  if ('iPhone' === navigator.platform) {
    span = document.getElementById('clickPhone');
    phone = span.innerText;    
    a = document.createElement('a');
    a.innerText = phone;
    a.setAttribute('href', 'tel:' + phone);
    span.innerText = '';
    span.appendChild(a);
  }
}());
