window.addEventListener("scroll", function() {
  const navbar = document.getElementById("navbar");
  if (window.scrollY > 50) {
    navbar.classList.add("scrolled");
    console.log('scrolling')
  } else {
    navbar.classList.remove("scrolled");
  }
});

const briefDescriptionOne = document.querySelector('.brief-description-and-timestamp-one');
const sections = document.querySelectorAll('.brief-description-and-timestamp-one')

sections.forEach(section => {
  const lines = section.querySelectorAll('.line-up, .line-left, .line-down, .line-right')
  section.addEventListener('mouseenter', () => {
    lines.forEach(line => {
      line.classList.add('active');
      console.log('hover')
    });
  });


  section.addEventListener('mouseleave', () => {
    lines.forEach(line => {
      line.classList.remove('active')
    })
  })

})


const aboutMeButton = document.querySelector('.about-me-image-button');
const aboutMeInfo = document.querySelector('.name')

aboutMeButton.addEventListener('click', ()=>{
  document.querySelector('.ending-tab-div').scrollIntoView({
    behavior: "smooth"
  })

  aboutMeInfo.classList.add('highlighted');

  setTimeout(()=>{
    aboutMeInfo.classList.remove('highlighted');
  }, 3000);
});

const evolutionHome = document.querySelectorAll('.main-logo-image, .page-title')

evolutionHome.forEach(element=>{
  element.addEventListener('click', ()=>{
    document.querySelector('.evolution-title-image').scrollIntoView({
      behavior: "smooth"
    });
  });
})
