# EmojiHunt
Given a random emoji, this program attampts to find all locations of the matching emoji in a randomly generated image. We have developed a method that can detect emojis extremely well while being invariant to a large number of transformations and noise. For a full report on our method and other methods we explored, please check out [our report](report.pdf)!

## Example
![emojiexample](https://user-images.githubusercontent.com/16991582/229385863-c4b9a686-fd3e-4611-b540-688f5affaec3.png)

# Methods
For our project we initially explored two methods, one which uses a classical computer vision approach and one which uses a deep learning approach. Ultimately, we ended up pursuing the deep learning approach as it yielded better results so the classical method notebook is included here mainly for completeness. For project scoring using the `official_test` method please use the ml_method.ipynb notebook, which contains our deep learning approach to the problem.

# Running
## Running on Google Collab
1. Upload one of the notebooks to Google colab (ml_method for running the `official_test` method)
2. If running the ml_method notebook, upload the model with the notebook or upload the model to the root of your Google drive
3. Run all cells sequentially

## Running Locally
1. No special setup required. Run all cells with the model in the same directory
