<Type Name="WcfCommunicationClient&lt;TServiceContract&gt;" FullName="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;">
  <TypeSignature Language="C#" Value="public class WcfCommunicationClient&lt;TServiceContract&gt; : Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient where TServiceContract : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfCommunicationClient`1&lt;class TServiceContract&gt; extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfCommunicationClient(Of TServiceContract)&#xA;Implements ICommunicationClient" />
  <TypeSignature Language="F#" Value="type WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt; = class&#xA;    interface ICommunicationClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TServiceContract">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TServiceContract">WCF サービス コントラクト</typeparam>
    <summary>
            によって作成された WCF クライアント<see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1" />Service Fabric サービスを使用して、通信するために<see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1" />です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Channel">
      <MemberSignature Language="C#" Value="public TServiceContract Channel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TServiceContract Channel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1.Channel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Channel As TServiceContract" />
      <MemberSignature Language="F#" Value="member this.Channel : 'ServiceContract" Usage="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt;.Channel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TServiceContract</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この通信のクライアントが使用する指定されたコントラクトの WCF チャネルを取得します。
            </summary>
        <value>この通信のクライアントが使用する指定されたコントラクトの WCF チャネル。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public System.Fabric.ResolvedServiceEndpoint Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ResolvedServiceEndpoint Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As ResolvedServiceEndpoint" />
      <MemberSignature Language="F#" Value="member this.Endpoint : System.Fabric.ResolvedServiceEndpoint with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt;.Endpoint" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient.Endpoint</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ResolvedServiceEndpoint</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定に、クライアントが接続されているサービス エンドポイント。
            </summary>
        <value>クライアントが接続されているサービス エンドポイント。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Finalize">
      <MemberSignature Language="C#" Value="~WcfCommunicationClient`1 ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Finalize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1.Finalize" />
      <MemberSignature Language="VB.NET" Value="Finalize ()" />
      <MemberSignature Language="F#" Value="override this.Finalize : unit -&gt; unit" Usage="wcfCommunicationClient.Finalize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトが、ガベージ コレクションによって収集される前に、リソースの解放とその他のクリーンアップ操作の実行を試みることができるようにします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenerName">
      <MemberSignature Language="C#" Value="public string ListenerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ListenerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1.ListenerName" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenerName As String" />
      <MemberSignature Language="F#" Value="member this.ListenerName : string with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt;.ListenerName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient.ListenerName</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、サービスのレプリカに、クライアントが接続されているインスタンスのリスナーの名前を設定します。
            </summary>
        <value>サービス レプリカまたはインスタンスに、クライアントが接続されているリスナーの名前。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolvedServicePartition">
      <MemberSignature Language="C#" Value="public System.Fabric.ResolvedServicePartition ResolvedServicePartition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ResolvedServicePartition ResolvedServicePartition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1.ResolvedServicePartition" />
      <MemberSignature Language="VB.NET" Value="Public Property ResolvedServicePartition As ResolvedServicePartition" />
      <MemberSignature Language="F#" Value="member this.ResolvedServicePartition : System.Fabric.ResolvedServicePartition with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt;.ResolvedServicePartition" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient.ResolvedServicePartition</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ResolvedServicePartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはパーティションとは、サービス レプリカまたはインスタンスとの通信に使用できるエンドポイントに関する情報が含まれていますが、解決済みのサービス パーティションを設定します。
            </summary>
        <value>解決済みのサービス パーティション。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>