<Type Name="OperationRetryControl" FullName="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl">
  <TypeSignature Language="C#" Value="public class OperationRetryControl" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationRetryControl extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationRetryControl" />
  <TypeSignature Language="F#" Value="type OperationRetryControl = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            例外の再試行ポリシーが通信にクライアントからサービスを指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationRetryControl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.Exception" />
      <MemberSignature Language="VB.NET" Value="Public Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ShouldRetry が false の場合、操作を報告する例外。 既定ではこれは、同じ例外として報告される例外は、場合によっては、ファクトリ可能性があります選択変換を意味のある例外を報告される例外です。
            </summary>
        <value>例外</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionId">
      <MemberSignature Language="C#" Value="public string ExceptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExceptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.ExceptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ExceptionId As String" />
      <MemberSignature Language="F#" Value="member this.ExceptionId : string with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.ExceptionId" />
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
        <value>この例外の一意の id。 この id は、この例外は、再試行回数の追跡に使用します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsTransient">
      <MemberSignature Language="C#" Value="public bool IsTransient { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsTransient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.IsTransient" />
      <MemberSignature Language="VB.NET" Value="Public Property IsTransient As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsTransient : bool with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.IsTransient" />
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
            ShouldRetry プロパティが true の場合、このプロパティは、クライアントとサービス間の通信チャネルが有効であるかどうかを示します。
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
      <MemberSignature Language="C#" Value="public int MaxRetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.MaxRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryCount : int with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.MaxRetryCount" />
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
            最大回数だけ、ShouldRetry が true の場合、この操作を再試行する必要があります。
            </summary>
        <value>最大再試行回数</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryDelay">
      <MemberSignature Language="C#" Value="public TimeSpan RetryDelay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan RetryDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.RetryDelay" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.RetryDelay : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.RetryDelay" />
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
            ShouldRetry が true の場合、この遅延後に操作を再試行する必要があります。
            </summary>
        <value>操作の再試行するまでの遅延時間</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public bool ShouldRetry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ShouldRetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.ShouldRetry" />
      <MemberSignature Language="VB.NET" Value="Public Property ShouldRetry As Boolean" />
      <MemberSignature Language="F#" Value="member this.ShouldRetry : bool with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.ShouldRetry" />
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
            操作を再試行する必要があるかどうかを示します。
            </summary>
        <value>ユーザーに、例外をスローする、操作を再試行する場合は true、false の場合</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>