# Input Field Text 

### Clear Text - Add Controller
```
TextEditingController _nameController = TextEditingController();
```
```
TextField(
  controller: _nameController,
  decoration: InputDecoration(
    border: OutlineInputBorder(),
    abel: Text("Name"),
    icon: Icon(Icons.person),
    suffixIcon: IconButton(onPressed: (){_nameController.clear();}, icon: Icon(Icons.close))
                
  ),
),
```

### Password hide/visibley
```
bool _password = true;
```
```
TextField(
  obscureText: _password,
  suffixIcon: IconButton(
    onPressed: () {
      setState(() {
        _password = !_password; // toggle
      });
    },
      icon: Icon(_password? Icons.visibility_off: Icons.visibility),
  ),
)
```



###### © All right reserved by **Faysal**





