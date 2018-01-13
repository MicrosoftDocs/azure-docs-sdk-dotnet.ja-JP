<Type Name="ServiceRemotingDispatchHeaders" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders">
  <TypeSignature Language="C#" Value="public class ServiceRemotingDispatchHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceRemotingDispatchHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceRemotingDispatchHeaders" />
  <TypeSignature Language="F#" Value="type ServiceRemotingDispatchHeaders = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ServiceRemoting メッセージと共に送信されるヘッダーを指定します。 このクラスは、サービスの独立したディスパッチャーと使用<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher" />例: ショート サーキットの (クライアントとサービスが同じプロセス内)。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRemotingDispatchHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MethodName">
      <MemberSignature Language="C#" Value="public string MethodName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MethodName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders.MethodName" />
      <MemberSignature Language="VB.NET" Value="Public Property MethodName As String" />
      <MemberSignature Language="F#" Value="member this.MethodName : string with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders.MethodName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            これは、要求に送信するメソッドの名前です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceInterfaceName">
      <MemberSignature Language="C#" Value="public string ServiceInterfaceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceInterfaceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders.ServiceInterfaceName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceInterfaceName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceInterfaceName : string with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders.ServiceInterfaceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            これは、リモート処理サービスのユーザー インターフェイスの完全な名前です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>