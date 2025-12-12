# Clear Input Field Text Click Icon

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
