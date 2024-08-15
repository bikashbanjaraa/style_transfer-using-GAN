# style transfer
Neural style transfer is an optimization technique used to take two images - a content image and a style reference image (such as an artwork by a famous painter) - and blend them together so the output image looks like the content image, but “painted” in the style of the style reference image.

This is implemented by optimizing the output image to match the content statistics of the content image and the style statistics of the style reference image. These statistics are extracted from the images using a convolutional network.


# STAR GAN: 
explore the work in StarGAN_v2_celeb_face_synthesizer.ipynb. StarGAN v2, the image translation model developed by Clova AI learns the mapping between different images. We used a Star GAN network pre-trained with the CelebA-HQ dataset as well as a set of celebrity faces across different genders, skin tones, facial features and facial/body modifications (tattoos, and plastic surgery) as our source image dataset, and the CelebA-HQ dataset as our reference image dataset. Our source dataset was split into two domains: female and male


# RESULT:
Our results showed that Distinct facial features such as strong jawlines and lips were propagated across different genders and skin tones into the generated/output images. For faces like The Weeknd’s that have undergone facial modifications (e.g. plastic surgery) We noticed these features also remained distinct in the generated images. However the generated images weren’t so realistic As expected, high-level features such as hairstyle, makeup, beard and skintone are followed from the reference images. However other features such as tattoos seemed to be preserved from the source image Similarly, The model preserved the pose and identity of the source images in most output images


![Alt text](https://github.com/bikashbanjaraa/style_transfer-using-GAN/raw/main/stargan-result/reference.jpg)
