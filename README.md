# 📚 Readability Checker    

Ever wondered what grade level your writing sits at?      
This C program estimates the **U.S. school grade** needed to understand a given piece of text using the **Coleman-Liau index** — the same metric used in real-world readability analysis.

---    

## 🚀 How It Works    

This program:    
- Counts the number of **letters**, **words**, and **sentences** in a text.    
- Calculates the **readability index** using the formula: index = 0.0588 * L - 0.296 * S - 15.8
- Where:    
- `L` = average number of **letters per 100 words**    
- `S` = average number of **sentences per 100 words**    
