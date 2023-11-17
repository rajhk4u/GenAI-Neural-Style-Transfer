# Neural-Style-Transfer Implentation Details
- Change the file path of the content_image as required.
- content_image = Image.open("/content/baby.jpg")
- content_image = np.array(Image.open("/content/baby.jpg").resize((400,400)))

- Change the file path of the style image as required.
- example = Image.open("/content/Artwork.jpg")
- style_image =  np.array(Image.open("/content/Artwork.jpg").resize((img_size, img_size)))
