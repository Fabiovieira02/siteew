document.addEventListener('DOMContentLoaded', () => {
    document.querySelectorAll('.read-more').forEach(button => {
      button.addEventListener('click', () => {
        const text = button.previousElementSibling;
        text.classList.toggle('expanded');
        button.textContent = text.classList.contains('expanded') ? 'Ver Menos' : 'Ver Mais';
      });
    });
  });
  