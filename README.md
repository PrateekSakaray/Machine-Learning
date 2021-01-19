# Video Memorability

## Aim and Approach
In this approach, model was built using text-based features and visual features. The visual feature that is used in this approach is C3D with its fc7 activations of the C3D network(provided in the dataset) as a feature vector to capture activity in the video [4]. The short-term and long-term memorability were modelled independently using Random Forest and SVR technique.

Following are the 6 approaches taken to predict the score
independently for both Dev-set and Test-set:
1) Random forest with Captions (textual description)
2) Random forest with C3D (visual feature description)
3) SVR with Captions (textual description)
4) SVR with C3D (visual description)
5) Random forest with Caption and C3D in a single
vector.
6) SVR with Captions and C3D in a single vector.
