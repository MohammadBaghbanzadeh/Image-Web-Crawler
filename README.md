## Bing Image Downloader

This is a Python script that allows you to easily download images from Bing using a keyword search. The script uses threading to achieve concurrent downloads of images and can be configured with options like output directory, number of threads, size filter, and a limit on the number of images downloaded.

### Requirements

- Python 3.x
- urllib

### Usage

1. Clone this repository or download the script directly.
2. Open the terminal and navigate to the directory containing the script.
3. Run the following command `python image_downloader.py` and enter the keyword for the image search query when prompted.
4. Once the script has completed execution, you will find the downloaded images in the `Crawled_Images` directory.

### Configuration

The script can be configured by changing the values of the following variables:

- `output_dir`: specifies the default output directory where images are stored (default: `./Crawled_Imgaes`)
- `url_header`: a dictionary containing the `User-Agent` key with a string representing the user agent for a web browser.
- `number_of_threads`: specifies the number of threads to use for concurrent downloading (default: 20)
- `large_image_filter`: specifies a filter to use for image size (default: "+filterui:imagesize-large")
- `filters`: specifies additional filters to use (default: '')
- `limit`: specifies a limit on the number of images downloaded (default: None)
