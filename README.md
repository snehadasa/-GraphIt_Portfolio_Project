**GraphIt**

![graphit Logo](https://datavizcatalogue.com/methods/images/top_images/area_graph.png "graphit logo")

**Overview**

This is the first step towards building the full web application: GraphIt. This is a part of the portfolio project. This project basically tracks the prices of the products from past 30 days and display the graph of it. This project will be integrating with the amazon api to get the data of the products and stores in the mysql.

**Files**

| Files | Description |
| ----- | ----------- |
| base_model.py | BaseModel defines all common attributes/methods for other classes |
| file_storage.py | serializes instances to a JSON file and deserializes JSON file to instances |
| __init__.py | create instance for application |
| console.py | entry point of the command interpreter |
| user.py | User class for user info which inherits from superclass BaseModel |
| state.py | State class for state info which inherits from superclass BaseModel |
| city.py | City class for city info which inherits from superclass BaseModel |
| amenity.py | Amenity class for amenity info which inherits from superclass BaseModel |
| place.py | Place class for place info which inherits from superclass BaseModel |
| review.py | Review class for review info which inherits from superclass BaseModel |

**Tests**

All the code are tested using Unittest Module.The unittest module provides a rich set of tools for constructing and running tests.

**Authors**

**Sneha Dasa Lakshminath** - @DasaSneha <https://github.com/snehadasa>
