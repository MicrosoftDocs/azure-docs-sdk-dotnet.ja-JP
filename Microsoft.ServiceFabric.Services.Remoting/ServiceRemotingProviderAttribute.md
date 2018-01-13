<Type Name="ServiceRemotingProviderAttribute" FullName="Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute">
  <TypeSignature Language="C#" Value="public abstract class ServiceRemotingProviderAttribute : Attribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ServiceRemotingProviderAttribute extends System.Attribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ServiceRemotingProviderAttribute&#xA;Inherits Attribute" />
  <TypeSignature Language="F#" Value="type ServiceRemotingProviderAttribute = class&#xA;    inherit Attribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Attribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.AttributeUsage(System.AttributeTargets.Assembly)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            これは、サービス インターフェイスが定義されているし、アセンブリで使用されるリモート処理に使用する既定のサービスのリモート処理プロバイダーを設定する属性の基本データ型です。
            </summary>
    <remarks>
      <para>
                サービス側では、この属性の実装がルックアップ<see cref="M:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingListener``1(``0,System.Fabric.StatefulServiceContext)" />と<see cref="M:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingListener``1(``0,System.Fabric.StatelessServiceContext)" />、既定値を作成するランタイムのメソッド<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />ステートフルおよびステートレス サービス。 
                </para>
      <para>
                クライアント側では、この属性の実装はルックアップ<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" />、既定値を作成するコンス トラクター<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />指定されていない場合。
                </para>
      <para>
                指定されたクライアント側に注意してください<see cref="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxy.Create``1(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String)" />方法は、既定値を作成する<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" />だけが最初に、同じプロバイダーが使用するまで 1 回とため、プロバイダーの参照が行わします。
                </para>
      <para>
                この属性が検索される順序は、次のように: <list type="number"> <item>エントリで<see cref="T:System.Reflection.Assembly" />メソッドを呼び出すことによって取得<see cref="M:System.Reflection.Assembly.GetEntryAssembly" /> </item> <item>で、<see cref="T:System.Reflection.Assembly" />をリモート インターフェイスを定義しますどのリスナーまたはプロキシを作成しています。</item></list></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRemotingProviderAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ServiceRemotingProviderAttribute クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactory">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory(class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.CreateServiceRemotingClientFactory(Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateServiceRemotingClientFactory (callbackClient As IServiceRemotingCallbackClient) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" Usage="serviceRemotingProviderAttribute.CreateServiceRemotingClientFactory callbackClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackClient" Type="Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient" />
      </Parameters>
      <Docs>
        <param name="callbackClient">クライアントの実装がコールバックをディスパッチする必要があります。</param>
        <summary>
            使用できるサービスのリモート処理クライアント ファクトリを作成、<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" />サービスのリモート インターフェイスのプロキシを作成します。
            </summary>
        <returns><see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactoryV2">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2 (Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2(class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2(Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateServiceRemotingClientFactoryV2 (callbackMessageHandler As IServiceRemotingCallbackMessageHandler) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingClientFactoryV2 : Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" Usage="serviceRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2 callbackMessageHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackMessageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler" />
      </Parameters>
      <Docs>
        <param name="callbackMessageHandler">クライアントの実装がコールバックをディスパッチする必要があります。</param>
        <summary>
            V2 サービス リモート処理クライアントのファクトリを作成して使用できる、<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" />サービスのリモート インターフェイスのプロキシを作成します。
            </summary>
        <returns><see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.CreateServiceRemotingListener(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="serviceRemotingProviderAttribute.CreateServiceRemotingListener (serviceContext, serviceImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
      </Parameters>
      <Docs>
        <param name="serviceContext">リモート処理のリスナーが構築される、サービスのコンテキスト。</param>
        <param name="serviceImplementation">サービス実装オブジェクト。</param>
        <summary>
            リモート処理サービス インターフェイスの V1 サービス リモート処理リスナーを作成します。
            </summary>
        <returns><see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />指定されたサービスのです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListenerV2">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2 (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.CreateServiceRemotingListenerV2(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingListenerV2 : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="serviceRemotingProviderAttribute.CreateServiceRemotingListenerV2 (serviceContext, serviceImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
      </Parameters>
      <Docs>
        <param name="serviceContext">リモート処理のリスナーが構築される、サービスのコンテキスト。</param>
        <param name="serviceImplementation">サービス実装オブジェクト。</param>
        <summary>
            リモート処理サービス インターフェイスの V2 サービス リモート処理リスナーを作成します。
            </summary>
        <returns><see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />指定されたサービスのです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemotingClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.RemotingClient RemotingClient { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Services.Remoting.RemotingClient RemotingClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.RemotingClient" />
      <MemberSignature Language="VB.NET" Value="Public Property RemotingClient As RemotingClient" />
      <MemberSignature Language="F#" Value="member this.RemotingClient : Microsoft.ServiceFabric.Services.Remoting.RemotingClient with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.RemotingClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.RemotingClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            RemotingClient を使用して、V1 または V2 のリモート クライアントが使用されているかを決定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemotingListener">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.RemotingListener RemotingListener { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Services.Remoting.RemotingListener RemotingListener" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.RemotingListener" />
      <MemberSignature Language="VB.NET" Value="Public Property RemotingListener As RemotingListener" />
      <MemberSignature Language="F#" Value="member this.RemotingListener : Microsoft.ServiceFabric.Services.Remoting.RemotingListener with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.RemotingListener" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.RemotingListener</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            RemotingListener を使用して、V1、V2 またはコンパクト モードにリスナーがある場合を決定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>