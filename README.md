# wdong
created new!
项目名称：第三方数据接口项目
项目代码：DataInterface
GIT库名称：DataInterface

public interface QueryValidatorServices extends Remote{
    public String querySingle(String userName_,
                              String password_,
                              String type_,
                              String param_) throws RemoteException;

    public String queryBatch(String userName_,
                             String password_,
                             String type_,
                             String param_) throws RemoteException;
}