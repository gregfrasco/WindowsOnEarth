To run:

```
python -m tf.retrain \
  --bottleneck_dir=tf_files/bottlenecks \
  --how_many_training_steps=2000 \
  --model_dir=tf_files/models/ \
  --summaries_dir=tf_files/training_summaries/inception_v3 \
  --output_graph=tf_files/retrained_graph.pb \
  --output_labels=tf_files/retrained_labels.txt \
  --architecture=inception_v3 \
  --image_dir=tf_files/images2
  --labels=tf_files/labels.txt
```