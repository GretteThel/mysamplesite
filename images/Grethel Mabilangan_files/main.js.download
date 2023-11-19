const toggleButtons = document.querySelectorAll ('.toggle');

toggleButtons.forEach (button => {
  button.addEventListener ('click', () => {
    const content = button.parentElement.children[1];

    if (content.className.indexOf ('hidden') > -1) {
      content.classList.remove ('hidden');
      button.children[0].className = "fa-solid fa-chevron-down";
    } else {
      content.classList.add ('hidden');
      button.children[0].className = "fa-solid fa-chevron-up";
    }
  });
});
