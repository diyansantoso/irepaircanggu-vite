
  # Irepair Portfolio Website

  This is a code bundle for Irepair Portfolio Website. The original project is available at https://www.figma.com/design/g9418UgJ4skunaDATHSTRa/Irepair-Portfolio-Website.

  ## Running the code

  Run `npm intall` to install the dependencies.

  Run `npm run dev` to start the development server.


  note :

install aos:
https://michalsnik.github.io/aos/

### Install using Yarn, Npm, Bower :
```
npm install aos --save
```

### Initialize AOS
```bash
<script>
  AOS.init();
</script>
```

### Import CSS and JS di App.js atau file komponen utama Anda agar animasi berfungsi.
```bash
import { useEffect } from 'react';
import AOS from 'aos';
import 'aos/dist/aos.css';


export default function App() {
  useEffect(() => {
    AOS.init({
      duration: 1000,
      once: true,
    });
  }, []);
```

  