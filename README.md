This is an implementation of the the DQN and Dueling architecture on the classical control problems in OpenAI gym - [CartPole-v0](https://gym.openai.com/envs/CartPole-v0/) and [MountainCar-v0](https://gym.openai.com/envs/MountainCar-v0/)

| CartPole                        | Mountain Car                          | 
| ------------------------------- | ------------------------------------- |
| ![CartPole](/docs/CartPole.gif) | ![MountainCar](/docs/MountainCar.gif) |


To run the program run- <br />
`python DQN_Implementation.py` with the following arguments <br />
| Argument                  | Description                                                                          |
| ------------------------- | ------------------------------------------------------------------------------------ |
|   |                                                         |  
| `--render=1 OR 0`         | variable to enable render(1) or not(0)                                               |
| `--train=1 OR 0`          | variable to train(1) the model or not(0)                                             |
| `--type=MODEL_TYPE`       | DQN,Dueling                                                                          |
| `--save_folder=FOLDER_DIR`| folder directory to save videos (Optional). Videos are not saved if nothing is given |
| `--model_file=FILE_DIR`   | File directory of saved model(Optional). Nothing is done if not given                |

| Argument         | Are           | Cool  |
| ------------- | -------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

Argument | Description
--- | --- 
`--env=ENVIRONMENT_NAME`| CartPole-v0, MountainCar-v0 
1 | 2

HyperParameters have been sectioned for easy alteration. You should be able to locate them easily by just searching 'Hyper' and alter them as per your convenience.
