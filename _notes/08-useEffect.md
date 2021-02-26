

```
  const [xxxData, setXXXData] = useState([])
  const loadXXXData = async() =>{
    const resp = await fetch('');
    const jsonData = await resp.json();

    setXXXData(jsonData);
  }


  useEffect(()=>{
    loadXXXData();
  },[]);
```


## CORS settings in API Gateway 