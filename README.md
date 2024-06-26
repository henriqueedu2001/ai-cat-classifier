# AI CAT CLASSIFIER
This is a CNN-based model for image cat breed classification. It receives a cat image and identifies the breed to which it belongs.

For this project, i used the **46 cat breeds** defined in the [purina](https://www.purina.com/cats/cat-breeds) website, as listed bellow.

|                     |                   |                  |                   |
|---------------------|-------------------|------------------|-------------------|
| Abyssinian          | American Bobtail  | American Curl    | American Shorthair|
| American Wirehair   | Balinese-Javanese | Bengal           | Birman            |
| Bombay              | British Shorthair | Burmese          | Chartreux         |
| Cornish Rex         | Devon Rex         | Egyptian Mau     | European Burmese  |
| Exotic Shorthair    | Havana Brown      | Himalayan        | Japanese Bobtail  |
| Korat               | LaPerm            | Maine Coon       | Manx              |
| Munchkin            | Norwegian Forest  | Ocicat           | Oriental          |
| Persian             | Peterbald         | Pixiebob         | Ragamuffin        |
| Ragdoll             | Russian Blue      | Savannah         | Scottish Fold     |
| Selkirk Rex         | Siamese           | Siberian         | Singapura         |
| Somali              | Sphynx            | Tonkinese        | Toyger            |
| Turkish Angora      | Turkish Van       |                  |                   |

## How to use this project?
First of all, we need to load the dataset in our local directory. You can do this in two ways: (a) creating your own dataset, via [bing image downloader](https://github.com/gurugaurav/bing_image_downloader) downloader tool; (b) downloading my dataset, stored in my personal google drive account.

## Downloading the dataset
To download the cat dataset, you can run the `download_cats.ipynb` notebook, that will **download 150 images per image category**. An image category is a combination of a cat breed and a cat view type. For example, with the views "front", "back", "side" and "face" ans the cat breed "bengal", we can generate the images categories "bengal cat front view", "bengal cat back view", "bengal cat side view" and "bengal cat face view".

To download my cat dataset, run the script `fetch_cats_dataset.py` in the directory of the project. Then, it will download my homemade and pre-processed dataset, from my google drive in to your local directory.