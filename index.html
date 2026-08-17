import os
from PIL import Image

# Android mipmap folder sizes in pixels
sizes = {
    "mipmap-mdpi": 48,
    "mipmap-hdpi": 72,
    "mipmap-xhdpi": 96,
    "mipmap-xxhdpi": 144,
    "mipmap-xxxhdpi": 192
}

# The required filenames for each folder
filenames = [
    "ic_launcher.png",
    "ic_launcher_foreground.png",
    "ic_launcher_round.png"
]

def generate_android_icons(source_image_path):
    try:
        # Open the master image
        img = Image.open(source_image_path)
        
        for folder, size in sizes.items():
            # Create the mipmap directory if it doesn't exist
            os.makedirs(folder, exist_ok=True)
            
            # Resize the image (using LANCZOS for high-quality downsampling)
            resized_img = img.resize((size, size), Image.Resampling.LANCZOS)
            
            # Save the three required files in the folder
            for filename in filenames:
                save_path = os.path.join(folder, filename)
                resized_img.save(save_path, "PNG")
                print(f"Generated: {save_path}")
                
        print("\nSuccess! All 15 assets have been generated.")
        
    except FileNotFoundError:
        print(f"Error: Could not find '{source_image_path}'. Please ensure it is in the same directory as this script.")

if __name__ == "__main__":
    # Target the specific file you uploaded
    generate_android_icons("1000170338.png")
