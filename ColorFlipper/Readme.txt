//Mind boggler
const getRandomNumber = () => {
  console.log(Math.random());
  console.log(colors.length);
  console.log(Math.random() * colors.length);
  console.log(Math.floor(Math.random() * colors.length));
  return Math.floor(Math.random() * colors.length);
};