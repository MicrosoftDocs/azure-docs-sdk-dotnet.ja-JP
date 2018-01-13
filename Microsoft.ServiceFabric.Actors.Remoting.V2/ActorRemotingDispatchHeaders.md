<Type Name="ActorRemotingDispatchHeaders" FullName="Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders">
  <TypeSignature Language="C#" Value="public class ActorRemotingDispatchHeaders : Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActorRemotingDispatchHeaders extends Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class ActorRemotingDispatchHeaders&#xA;Inherits ServiceRemotingDispatchHeaders" />
  <TypeSignature Language="F#" Value="type ActorRemotingDispatchHeaders = class&#xA;    inherit ServiceRemotingDispatchHeaders" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ServiceRemoting メッセージと共に送信されるヘッダーを指定します。 このクラスは、サービスの独立したディスパッチャーと使用<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Runtime.ActorServiceRemotingDispatcher" />例: ショート サーキットの (クライアントとサービスが同じプロセス内)。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorRemotingDispatchHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorId">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.ActorId ActorId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.ActorId ActorId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders.ActorId" />
      <MemberSignature Language="VB.NET" Value="Public Property ActorId As ActorId" />
      <MemberSignature Language="F#" Value="member this.ActorId : Microsoft.ServiceFabric.Actors.ActorId with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders.ActorId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.ActorId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            リモート処理する要求がへのディスパッチ ActorId
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorInterfaceName">
      <MemberSignature Language="C#" Value="public string ActorInterfaceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActorInterfaceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders.ActorInterfaceName" />
      <MemberSignature Language="VB.NET" Value="Public Property ActorInterfaceName As String" />
      <MemberSignature Language="F#" Value="member this.ActorInterfaceName : string with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders.ActorInterfaceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            これは、ユーザー IActor インターフェイスの完全な名前です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CallContext">
      <MemberSignature Language="C#" Value="public string CallContext { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CallContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders.CallContext" />
      <MemberSignature Language="VB.NET" Value="Public Property CallContext As String" />
      <MemberSignature Language="F#" Value="member this.CallContext : string with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders.CallContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            これを使用して、アクターにこれは再入を制限できます。 これは、省略可能なヘッダーです。 指定されていない場合。 Guid を追加し、この要求に対して、callContext として使用し、既存の callContext を確認します。
            既存 callContext が存在しない場合にランダムな Guid が割り当てられます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>