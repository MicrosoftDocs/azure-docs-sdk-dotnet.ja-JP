<Type Name="ExceptionHandlingRetryResult" FullName="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult">
  <TypeSignature Language="C#" Value="public sealed class ExceptionHandlingRetryResult : Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ExceptionHandlingRetryResult extends Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ExceptionHandlingRetryResult&#xA;Inherits ExceptionHandlingResult" />
  <TypeSignature Language="F#" Value="type ExceptionHandlingRetryResult = class&#xA;    inherit ExceptionHandlingResult" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            クライアントからサービスへの要求を再試行できる場合は、結果を処理する例外を示す
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionHandlingRetryResult (Exception exception, bool isTransient, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, int maxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Exception exception, bool isTransient, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, int32 maxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.#ctor(System.Exception,System.Boolean,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult : Exception * bool * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * int -&gt; Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult (exception, isTransient, retrySettings, maxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="isTransient" Type="System.Boolean" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="maxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="exception">この例外は、再試行する必要があります。</param>
        <param name="isTransient">
            一時的な例外が再試行可能なことを示します。
            一時的な再試行可能な例外はクライアントからサービスへの通信チャネルがまだ存在します。
            非一時的な再試行可能な例外が、もう一度は再試行する前に、サービス エンドポイントを解決する必要があります。
            </param>
        <param name="retrySettings">再試行する前に待機する間隔を retrySettings でにわかっています。</param>
        <param name="maxRetryCount">最大回数 exceptionId パラメーターによって識別される例外を再試行する必要があります。</param>
        <summary>
            指定した引数を使用して ExceptionHandlingRetryResult をインスタンス化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionHandlingRetryResult (Exception exception, bool isTransient, TimeSpan retryDelay, int maxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Exception exception, bool isTransient, valuetype System.TimeSpan retryDelay, int32 maxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.#ctor(System.Exception,System.Boolean,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult : Exception * bool * TimeSpan * int -&gt; Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult (exception, isTransient, retryDelay, maxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="isTransient" Type="System.Boolean" />
        <Parameter Name="retryDelay" Type="System.TimeSpan" />
        <Parameter Name="maxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="exception">この例外は、再試行する必要があります。</param>
        <param name="isTransient">
            一時的な例外が再試行可能なことを示します。
            一時的な再試行可能な例外はクライアントからサービスへの通信チャネルがまだ存在します。
            非一時的な再試行可能な例外が、もう一度は再試行する前に、サービス エンドポイントを解決する必要があります。
            </param>
        <param name="retryDelay">再試行する前に待機する間隔</param>
        <param name="maxRetryCount">例外パラメーターで指定された例外を再試行する必要がありますの最大回数。</param>
        <summary>
            指定した引数を使用して ExceptionHandlingRetryResult をインスタンス化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionHandlingRetryResult (string exceptionId, bool isTransient, TimeSpan retryDelay, int maxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string exceptionId, bool isTransient, valuetype System.TimeSpan retryDelay, int32 maxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.#ctor(System.String,System.Boolean,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (exceptionId As String, isTransient As Boolean, retryDelay As TimeSpan, maxRetryCount As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult : string * bool * TimeSpan * int -&gt; Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult (exceptionId, isTransient, retryDelay, maxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exceptionId" Type="System.String" />
        <Parameter Name="isTransient" Type="System.Boolean" />
        <Parameter Name="retryDelay" Type="System.TimeSpan" />
        <Parameter Name="maxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="exceptionId">再試行する必要がある例外の識別子です。</param>
        <param name="isTransient">
            一時的な例外が再試行可能なことを示します。
            一時的な再試行可能な例外はクライアントからサービスへの通信チャネルがまだ存在します。
            非一時的な再試行可能な例外が、もう一度は再試行する前に、サービス エンドポイントを解決する必要があります。
            </param>
        <param name="retryDelay">再試行する前に待機する間隔</param>
        <param name="maxRetryCount">最大回数 exceptionId パラメーターによって識別される例外を再試行する必要があります。</param>
        <summary>
            指定した引数を使用して ExceptionHandlingRetryResult をインスタンス化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionId">
      <MemberSignature Language="C#" Value="public string ExceptionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExceptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.ExceptionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExceptionId As String" />
      <MemberSignature Language="F#" Value="member this.ExceptionId : string" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.ExceptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            例外の種類を一意に識別する文字列。
            </summary>
        <value>
            この例外の一意の id。 この id は、この例外は、再試行回数の追跡に使用します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsTransient">
      <MemberSignature Language="C#" Value="public bool IsTransient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsTransient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsTransient As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsTransient : bool" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            一時的な再試行可能な例外はクライアントからサービスへの通信チャネルがまだ存在します。
            非一時的な再試行可能な例外が、もう一度は再試行する前に、サービス エンドポイントを解決する必要があります。
            </summary>
        <value>
            true は、一時的な例外が再試行可能であることを示します。
            false は、非一時的な例外が再試行可能であることを示します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryCount">
      <MemberSignature Language="C#" Value="public int MaxRetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxRetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryCount : int" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            最大回数だけこの種類の例外与える前に再試行する必要があります。
            既定値は整数です。MaxValue
            </summary>
        <value>最大再試行回数</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryDelay">
      <MemberSignature Language="C#" Value="public TimeSpan RetryDelay { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan RetryDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetryDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.RetryDelay : TimeSpan" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作は、この遅延後に再試行する必要があります。
            </summary>
        <value>操作の再試行するまでの遅延時間</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>