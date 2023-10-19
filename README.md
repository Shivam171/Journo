# 📝 Journo: Your Personal Diary in C++

This is a simple command-line diary program implemented in C++. The program allows users to create, view, protect with passwords, and manage diary entries. Below, you'll find details about its features, implementation, use cases, technologies and libraries used, and what you can learn from this project.

## 🧰 Features

1. **Add New Diary Entry:** Users can create new diary entries with a subject, date, content, and optional password protection. Passwords can be added with password hints for recovery.

2. **View Diary Entries:** Users can view a list of diary entries, which includes the subject and date of each entry. Password-protected entries are displayed with a prompt to enter the password for viewing.

3. **Delete Diary Entry:** Users can delete diary entries. Password-protected entries require the correct password to be deleted.

4. **Search Diary Entries:** Users can search for diary entries by subject. The search results include subject and date. Password-protected entries provide instructions for viewing the content.

## ⚙️ Implementation

### Add New Diary Entry
- **Subject and Content:** Users can provide a subject and content for a diary entry. The program uses `getline` to read multi-line content.
- **Date and Time:** The program automatically records the date and time of each entry using the C++ Standard Library's date/time functions.
- **Password Protection:** Users are prompted to protect an entry with a password, and the program stores the password and an optional password hint.
- **File I/O:** Entries are written to a text file for persistence.

### View Diary Entries
- **Reading from File:** The program reads diary entries from a text file using file input/output operations.
- **Password Protection:** For password-protected entries, the program prompts the user for the password and displays a password hint if the password is incorrect.

### Delete Diary Entry
- **Entry Deletion:** Users can delete a diary entry by specifying its number. Password-protected entries require the correct password for deletion.
- **File Update:** After deletion, the program updates the text file to reflect the changes.

### Search Diary Entries
- **Subject-Based Search:** Users can search for diary entries by subject, and the program displays matching entries.
- **Password Protection in Search:** For password-protected entries, the program informs users how to view the content.

## 🤷‍♂️ Use Cases

- **Personal Diary:** The program can be used as a personal diary for recording thoughts, events, or memories.
- **Password Protection:** It provides a simple way to add a layer of security for sensitive diary entries.
- **Data Persistence:** Diary entries are stored in a text file, allowing users to keep a record of their entries over time.

## 🧑‍💻 Technologies and Libraries

- **C++:** The project is implemented in C++.
- **Standard Library:** The C++ Standard Library is used for input/output operations, string manipulation, and date/time handling.

## 🤔 What You Can Learn

- **File I/O:** The project includes file input/output operations for data storage, allowing you to understand how to read from and write to files in C++.
- **User Input Handling:** You can learn how to handle user input and validate it for various use cases, including password protection.
- **Password Protection:** Basic password protection is implemented, which can serve as a starting point for more advanced security features.
- **Project Organization:** The project structure and menu-based interface can provide insights into organizing and managing larger C++ projects.

## 🤝 Contribute

Feel free to contribute to this project by forking it and making changes. I welcome your updates and encourage you to star the repository if you find it helpful.

**How to Contribute:**
1. Fork the repository or Clone it.
2. Create your feature branch: `git checkout -b feature/my-new-feature`.
3. Commit your changes: `git commit -am 'Add some feature'`.
4. Push to the branch: `git push origin feature/my-new-feature`.
5. Submit a pull request.

Let's collaborate and make Journo even better together!

## 🪪 License

This project is available under the [MIT License](LICENSE).
