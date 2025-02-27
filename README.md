#   Steganography Image Encoder    

A modern Python-based GUI tool for concealing messages within images using steganography. Developed with Python and Tkinter.  


    🚀 Features    

- 🖼️ Supports PNG, JPG, and BMP formats  
- 📝 Input text manually or from files  
- 🔐 Password-protected encoding/decoding  
- 🎨 Sleek dark-themed interface  
- 📊 Live status updates  
- ⚡ Fast encoding & decoding  
- 💾 High-quality PNG output  

    🔧 Installation    

1. Clone the repository:  
   ```bash
   git clone github.com/Ziaulislambhatt/steganography.git
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  

    📌 Usage    

1.   Run the application:    
   ```bash
   python steganography_app.py
   ```  
2.   Encoding a Message:    
   - Select an image  
   - Enter or load a secret message  
   - Set a password for security  
   - Click "Encode Message" and save the output  

3.   Decoding a Message:    
   - Select the encoded image  
   - Enter the password  
   - Click "Decode Message" to reveal the hidden text  

    🛠️ Technical Details    

- LSB (Least Significant Bit) steganography  
- Password-based security  
- Custom pixel manipulation via OpenCV  
- Message length stored in metadata  

    📋 Requirements    

- Python 3.8+  
- OpenCV (opencv-python)  
- Pillow  
- NumPy  
- Tkinter (built-in)  

    📜 License    

Licensed under the MIT License – see [LICENSE](LICENSE).  

    🙏 Acknowledgments    

- OpenCV team for image processing tools  
- Inspired by various steganography methods  

    ⚠️ Security Disclaimer    

For educational purposes only. Use established encryption for sensitive data. Developed with Automated GPT (Claude Sonet 3.5).  

    👨‍💻 Author    

Zia Ud Din Akbar – [GitHub](github.com/Ziaulislambhatt/steganography)  

    ⭐ Support    

If you find this useful, consider giving it a ⭐!
