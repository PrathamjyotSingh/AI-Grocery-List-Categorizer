# 🛒 Grocery List Categorizer

This project uses **Ollama's Llama3.2 model** to automatically categorize and sort grocery items into appropriate sections such as **Produce, Dairy, Meat, Bakery, Beverages, etc.** The categorized list is saved to a file for easy access.

---

## 📌 Features
- ✅ Reads an uncategorized grocery list from a file
- ✅ Uses an AI model to categorize items into relevant sections
- ✅ Sorts items alphabetically within each category
- ✅ Saves the categorized list to an output file

---

## 🔧 Installation

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/grocery-list-categorizer.git
cd grocery-list-categorizer
```

2️⃣ Install Dependencies
Ensure you have Ollama installed. If not, install it:

```sh
pip install ollama
```
3️⃣ Run the Application
```sh
python categorize_grocery.py
```

📂 Project Structure
```bash
📁 grocery-list-categorizer
│── 📂 data
│   ├── grocery_list.txt  # Input grocery list
│   ├── categorized_grocery_list.txt  # Categorized output file
│── categorize_grocery.py  # Main script
│── README.md  # Project documentation
```
📜 Usage
1️⃣ Prepare an input file:

Create a text file at ./data/grocery_list.txt
Add grocery items (one per line)
Example:
```
nginx
Copy
Edit
milk
bread
chicken
lettuce
cereal
apple
cheese
orange juice
```
2️⃣ Run the script:

```sh
python categorize_grocery.py
```
3️⃣ Check the output file:

The categorized grocery list will be saved in ./data/categorized_grocery_list.txt
Example Output:

```
🍏 **Produce**
- Apple
- Lettuce

🥛 **Dairy**
- Cheese
- Milk

🥩 **Meat**
- Chicken

🥖 **Bakery**
- Bread

🥤 **Beverages**
- Orange Juice

🍞 **Cereal & Grains**
- Cereal
```
🚀 Future Improvements

📝 GUI Support using Streamlit

🔄 Real-time Categorization with live updates

📦 Integration with Shopping Apps


🤝 Contributing
Pull requests are welcome! Feel free to open issues and suggest improvements.

📜 License
This project is licensed under the MIT License.











