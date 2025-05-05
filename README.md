# Detecting-steganography-with-tools-like-StegExpose-analyzing-file-signatures
## AIM:
To detect hidden data using steganography detection tools like StegExpose and analyze file signatures for authenticity and manipulation.

## DESIGN STEPS:
### Step 1:
Install StegExpose or use the JAR version to detect steganography in image files.

### Step 2:
Run StegExpose on a directory of suspected image files using the command:

### Step 3:
Analyze file signatures using tools like file, binwalk, or xxd to check for inconsistencies or embedded content.

## PROCEDURE:
• Download a .jpeg image from a trusted website or use own image.

<img width="400" alt="image" src="https://github.com/user-attachments/assets/8b00c28b-83a4-4224-b603-9e2b9a77f910"/>

Create a text file named secret with a confidential message:

<img width="400" alt="image" src="https://github.com/user-attachments/assets/4301d7e9-ecc4-487e-a389-41dbc2398fa0"/>

# Step 2: Install and Verify Steghide Tool
• To install Steghide on Kali linux,run:

• Confirm the installation by checking its version

<img width="400" alt="image" src="https://github.com/user-attachments/assets/31608271-d812-4679-9225-81462b14d18c"/>

# Step 3: Embed the Secret Message into the Image
• Use the following command to embed secret

<img width="400" alt="image" src="https://github.com/user-attachments/assets/d4195488-0b20-4b44-abdf-b623e95fa18e"/>

<img width="400" alt="image" src="https://github.com/user-attachments/assets/b27f0a1b-4983-4fe1-9919-b49735c2e285"/>


# Step 4: Delete the Original Secret File
• After embedding, delete the plaintext file:

<img width="400" alt="image" src="https://github.com/user-attachments/assets/b27f0a1b-4983-4fe1-9919-b49735c2e285"/>

## OUTPUT:
List of Images with Steganography Detection Scores and File Signature Details

<img width="400" alt="image" src="https://github.com/user-attachments/assets/3e83c0bd-c3de-4c53-b29b-31fd5c11abc3"/>


# Step 2: Verify the Extracted Message
• Display the extracted file content to verify:

• Ensure the message matches the original secret content.

• Another command to see the same secret message is

# Step 3: Retrieve Information About the Embedded Data

• To gather details about embedded content in the image:

<img width="400" alt="image" src="https://github.com/user-attachments/assets/237da533-1f10-496c-b8b6-09655e61d69b"/>


• This will display file type, size, and whether data is embedded.
## RESULT:
Hidden data was successfully detected and file signatures were analyzed for irregularities.
