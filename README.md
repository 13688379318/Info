# Info

Toast.cancle是异步的。容易出现问题。
解决方案 if (toast != null && toast.getView() != null && toast.getView().isShown()) { toast.cancle }
