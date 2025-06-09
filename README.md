# Help Translate Our Launcher

Thank you for your interest in making our launcher accessible to more people around the world! By translating it into your language, you help create a better experience for users everywhere.

## Two Ways to Contribute

We offer two methods for contributing. The first is the standard GitHub method, and the second is a simpler alternative if you're not comfortable with Git.

### Option 1: The GitHub Method (Recommended)

This is the best way to contribute if you're familiar with GitHub.

1.  **Fork the Repository**  
    Click the `Fork` button at the top-right corner of this page. This will create a personal copy of the project in your own GitHub account.

2.  **Find or Create Your Language File**  
    Navigate to the project files in your fork. Look for a `.json` file for your language (e.g., `pt-BR.json` for Brazilian Portuguese). If it doesn't exist, you can create one by copying `en.json`. Please use the appropriate [ISO 639-1 language code](https://www.loc.gov/standards/iso639-2/php/code_list.php) for the filename.

3.  **Translate the Content**  
    Edit the file and translate the text. **Important:** Only translate the text on the right side (the "value"), not the text on the left (the "key").

    *   **DO:**
        ```json
        "dashboard": "Panel de control",
        ```
    *   **DON'T:**
        ```json
        "panel-de-control": "Panel de control",
        ```

4.  **Submit a Pull Request**  
    Once you are finished, go to the "Pull Requests" tab in the original repository and click "New Pull Request". GitHub will guide you through the process of submitting your changes for review. Please provide a simple description, like "Added Spanish translation" or "Updated German translation."

---

### Option 2: The Simple Method (No Git Required)

If you're not comfortable with forks and pull requests, no problem! We still want your help.

1.  Download the `en.json` file from this repository.
2.  Translate it using any text editor.
3.  Contact **Boci** or **Juão** on our community channels and send them your translated file. They will handle the process of adding it to the project for you!

## Translation Guidelines

To ensure consistency, please keep these points in mind:

*   **Tone:** Aim for a clear and friendly tone. It shouldn't be overly formal or too casual. Clarity is the main goal.
*   **Variables:** Some phrases contain variables like `{0}` or `{1}`. These are placeholders that the application will replace with a value (like an account name). Please keep these variables in your translation exactly as they are.

    *   **Example:**
        ```json
        "injector_launched": "Injector launched successfully.\nAccount: {0}\nRegion: {1}"
        ```
    *   **Correct Translation (Spanish):**
        ```json
        "injector_launched": "El inyector se inició correctamente.\nCuenta: {0}\nRegión: {1}"
        ```

We truly appreciate your time and effort in helping us improve the launcher. Thank you for being a part of our community