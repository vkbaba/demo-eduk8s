#### Click text to execute
カレントディレクトリを移動してください。

```execute
echo "execute in terminal 1"
```
Pod を作成するマニフェストをapply します。

```execute
kubectl apply -f nginx.yaml
```

Pod が正しく作成されているかを確認します。

```execute
kubectl get pod
```

Good Job!!

