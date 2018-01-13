<Type Name="OperationResponse" FullName="Microsoft.Azure.DataLake.Store.OperationResponse">
  <TypeSignature Language="C#" Value="public class OperationResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.OperationResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationResponse" />
  <TypeSignature Language="F#" Value="type OperationResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            クラスは、1 つの操作の応答をカプセル化します。 使用可能な操作が Operation.cs の 1 つの操作では、Http 要求を複数回 (1 つ以上の再試行) を送信します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.OperationResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public string Error { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.OperationResponse.Error" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Error As String" />
      <MemberSignature Language="F#" Value="member this.Error : string" Usage="Microsoft.Azure.DataLake.Store.OperationResponse.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作の最後の Http 要求を送信中に、コードによりキャッチ、他のエラー
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ex">
      <MemberSignature Language="C#" Value="public Exception Ex { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Ex" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.OperationResponse.Ex" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Ex As Exception" />
      <MemberSignature Language="F#" Value="member this.Ex : Exception" Usage="Microsoft.Azure.DataLake.Store.OperationResponse.Ex" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            その他の操作の最後の Http 要求を送信中にスローされる例外
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionHistory">
      <MemberSignature Language="C#" Value="public string ExceptionHistory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExceptionHistory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.OperationResponse.ExceptionHistory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExceptionHistory As String" />
      <MemberSignature Language="F#" Value="member this.ExceptionHistory : string" Usage="Microsoft.Azure.DataLake.Store.OperationResponse.ExceptionHistory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この操作のすべての再試行の例外の履歴。 これは、必要がありますをリセットできませんのすべての再試行
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpMessage">
      <MemberSignature Language="C#" Value="public string HttpMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HttpMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.OperationResponse.HttpMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HttpMessage As String" />
      <MemberSignature Language="F#" Value="member this.HttpMessage : string" Usage="Microsoft.Azure.DataLake.Store.OperationResponse.HttpMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Http メッセージのこの操作の最後の Http 要求の出力/
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpStatus">
      <MemberSignature Language="C#" Value="public System.Net.HttpStatusCode HttpStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Net.HttpStatusCode HttpStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.OperationResponse.HttpStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HttpStatus As HttpStatusCode" />
      <MemberSignature Language="F#" Value="member this.HttpStatus : System.Net.HttpStatusCode" Usage="Microsoft.Azure.DataLake.Store.OperationResponse.HttpStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpStatusCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この操作の最後の Http 要求のサブコード コード
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSuccessful">
      <MemberSignature Language="C#" Value="public bool IsSuccessful { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSuccessful" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.OperationResponse.IsSuccessful" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSuccessful As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSuccessful : bool" Usage="Microsoft.Azure.DataLake.Store.OperationResponse.IsSuccessful" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            最後の Http 要求が操作の成功したかどうか
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastCallLatency">
      <MemberSignature Language="C#" Value="public long LastCallLatency { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastCallLatency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.OperationResponse.LastCallLatency" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastCallLatency As Long" />
      <MemberSignature Language="F#" Value="member this.LastCallLatency : int64" Usage="Microsoft.Azure.DataLake.Store.OperationResponse.LastCallLatency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作の最後の要求の合計待機時間
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpCode">
      <MemberSignature Language="C#" Value="public string OpCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OpCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.OperationResponse.OpCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OpCode As String" />
      <MemberSignature Language="F#" Value="member this.OpCode : string" Usage="Microsoft.Azure.DataLake.Store.OperationResponse.OpCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作コード
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteExceptionJavaClassName">
      <MemberSignature Language="C#" Value="public string RemoteExceptionJavaClassName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemoteExceptionJavaClassName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.OperationResponse.RemoteExceptionJavaClassName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteExceptionJavaClassName As String" />
      <MemberSignature Language="F#" Value="member this.RemoteExceptionJavaClassName : string" Usage="Microsoft.Azure.DataLake.Store.OperationResponse.RemoteExceptionJavaClassName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この操作の最後の Http 要求に対するサーバーから返されたリモート例外 java クラス名
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteExceptionMessage">
      <MemberSignature Language="C#" Value="public string RemoteExceptionMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemoteExceptionMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.OperationResponse.RemoteExceptionMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteExceptionMessage As String" />
      <MemberSignature Language="F#" Value="member this.RemoteExceptionMessage : string" Usage="Microsoft.Azure.DataLake.Store.OperationResponse.RemoteExceptionMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この操作の最後の Http 要求に対するサーバーから返されたリモート例外メッセージ
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteExceptionName">
      <MemberSignature Language="C#" Value="public string RemoteExceptionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemoteExceptionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.OperationResponse.RemoteExceptionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteExceptionName As String" />
      <MemberSignature Language="F#" Value="member this.RemoteExceptionName : string" Usage="Microsoft.Azure.DataLake.Store.OperationResponse.RemoteExceptionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この操作の最後の Http 要求に対するサーバーから返されたリモート例外名
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public string RequestId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.OperationResponse.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestId As String" />
      <MemberSignature Language="F#" Value="member this.RequestId : string" Usage="Microsoft.Azure.DataLake.Store.OperationResponse.RequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求 Id または操作の最後の要求に対するサーバーから返されたトレース ID
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reset">
      <MemberSignature Language="C#" Value="public void Reset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Reset() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.OperationResponse.Reset" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reset ()" />
      <MemberSignature Language="F#" Value="member this.Reset : unit -&gt; unit" Usage="operationResponse.Reset " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            すべての memebers 例外、ExceptionHistory をリセットします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retries">
      <MemberSignature Language="C#" Value="public int Retries { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Retries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.OperationResponse.Retries" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Retries As Integer" />
      <MemberSignature Language="F#" Value="member this.Retries : int" Usage="Microsoft.Azure.DataLake.Store.OperationResponse.Retries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作の再試行の回数
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenAcquisitionLatency">
      <MemberSignature Language="C#" Value="public long TokenAcquisitionLatency { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TokenAcquisitionLatency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.OperationResponse.TokenAcquisitionLatency" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TokenAcquisitionLatency As Long" />
      <MemberSignature Language="F#" Value="member this.TokenAcquisitionLatency : int64" Usage="Microsoft.Azure.DataLake.Store.OperationResponse.TokenAcquisitionLatency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作の最後の要求のトークンの取得の合計待機時間
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>