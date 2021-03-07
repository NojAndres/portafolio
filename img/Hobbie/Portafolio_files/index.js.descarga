((items) => {
  const $menubt = items.querySelector('.menu-btn'),
    $menu = items.querySelector('.menu');

  $menubt.addEventListener('click', (e) => {
    $menubt.firstElementChild.classList.toggle('none');
    $menubt.lastElementChild.classList.toggle('none');
    $menu.classList.toggle('is-active');
  });

  items.addEventListener('click', (e) => {
    if (!e.target.matches('.menu a')) return false;

    $menubt.firstElementChild.classList.remove('none');
    $menubt.lastElementChild.classList.add('none');
    $menu.classList.remove('is-active');
  });
})(document);

((header) => {
  const $header = header.querySelector('.header');

  if(document.scrollY < 200){
    $header.classList.toggle(".header.move")
  }
})(document)