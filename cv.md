1.  Darkhan Akhmetov
2.  Email: darkhanahmetov2005@gmail.com, darkhanahmetov228@gmail.com
3.  I want to be Full-stack developer, I mad about programming and I am want to study and learn everything, like Node.js React Vue and etc
4.  Html(Pug) CSS, SCSS, Sass, Stylus, Gulp, JS, Bootstrap, PHP, learning react
5.  const forms = document.querySelector('form');
    const messages = {
    loading: 'Загрузка',
    success: 'Спасибо! Мы скоро с вами свяжемся',
    failure: 'Что-то пошло не так...'
    };
    const postData = (form) => {
    form.addEventListener('submit', (event) => {
    event.preventDefault();

          const statusMessage = document.createElement("div");
          statusMessage.classList.add('status');
          statusMessage.textContent = messages.loading;
          form.append(statusMessage);

          const xhr = new XMLHttpRequest();
          xhr.open('POST', 'server.php');
          xhr.setRequestHeader('Content-type', 'multipart/form-data');

          const formData = new FormData(form);

          xhr.send(formData);

          xhr.addEventListener('load', () => {
            if (xhr.status === 200) {
              console.log(xhr.response);
            }
          });

    });
    };

6.  Some Hakatons, many projects, Innopolis Open and other olympiads
7.  Glo Academy, Udemy, School
8.  I am learning English for 5 years, and I have Intermediate level, but I am trying to improve it
