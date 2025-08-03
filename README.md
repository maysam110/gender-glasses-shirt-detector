Here’s the full `README.md` for your GitHub repository — **excluding the code**, and written in a professional, clear, and engaging format that’s ideal for public release:

---

```markdown
# 🧠 Image Attribute Classification Pipeline

This project provides a complete image analysis pipeline that can identify **Gender**, **Glasses Presence**, and **Shirt Color** from a single photo. It combines **deep learning**, **pose estimation**, and **computer vision** techniques into one powerful, easy-to-use system.

---

## 📌 Key Features

- ✅ Predicts **Gender** using a trained convolutional neural network.
- ✅ Detects if the person is **Wearing Glasses**.
- ✅ Uses **pose landmarks** to locate and crop the **shirt region**.
- ✅ Applies **KMeans clustering** to identify the **dominant shirt color**.
- ✅ Converts RGB to a readable **color name** using the `webcolors` library.
- 🎯 Designed for both research and practical applications (identity verification, user profiling, and more).

---

## 🧠 Technologies Used

- **PyTorch** for model inference
- **MediaPipe** for pose detection
- **OpenCV** for image processing
- **scikit-learn** for color clustering
- **Matplotlib** for image visualization
- **Pillow** for image loading
- **Webcolors** for converting RGB to HTML color names

---

## 📁 Project Structure

```

.
├── gender\_25epoch\_model.pth         # Trained model for gender prediction
├── glasses\_model.pth                # Trained model for glasses detection
├── README.md                        # This file

````

---

## 🚀 How to Run

1. Clone the repository.
2. Install the dependencies 
3. Place your image 
4. Run the Python script to see predictions for:
   - Gender
   - Glasses
   - Shirt Color (with visualization)

---

## 📥 Output Example

Once you run the script, you will get output like this:

```json
{
  "gender": "Male",
  "glasses": "Wearing Glasses",
  "shirt_color": "blue"
}
````

Additionally, the cropped shirt region will be displayed with the detected color as the title.

---

## ⚙️ Model Details

* **Gender Model**: Trained on a balanced dataset of male/female faces for 25 epochs using a CNN architecture.
* **Glasses Model**: Binary classification (glasses / no glasses) using the same CNN backbone.
* Both models expect RGB images resized to **224x224** pixels.

---

## 🔒 Notes

* Make sure your input image shows the upper body clearly for accurate pose detection.
* If no pose landmarks are detected, shirt color may not be predicted.

---

## 👨‍💻 Author

Made with ❤️ by \[Your Name or GitHub Username]
Feel free to **fork**, **contribute**, or **report issues**.

---

## 📃 License

This project is open-source under the MIT License. You're free to use, modify, and distribute with proper attribution.

```

---

