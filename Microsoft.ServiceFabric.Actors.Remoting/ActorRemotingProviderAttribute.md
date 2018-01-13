<Type Name="ActorRemotingProviderAttribute" FullName="Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute">
  <TypeSignature Language="C#" Value="public abstract class ActorRemotingProviderAttribute : Attribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ActorRemotingProviderAttribute extends System.Attribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ActorRemotingProviderAttribute&#xA;Inherits Attribute" />
  <TypeSignature Language="F#" Value="type ActorRemotingProviderAttribute = class&#xA;    inherit Attribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
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
            これは、アクター インターフェイスが定義されているまたはアセンブリで使用されるリモート処理に使用する既定のリモート処理のプロバイダーを設定する属性の基本データ型です。
            </summary>
    <remarks>
      <para>
                サービス側では、この属性の実装はルックアップ<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorService" />デフォルトを作成する<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />にします。 
                </para>
      <para>
                クライアント側では、この属性の実装はルックアップ<see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" />、既定値を作成するコンス トラクター<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />指定されていない場合。
                </para>
      <para>
                クライアント側のアクター プロキシは、静的なを使用して作成されたときに<see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" />クラスで、既定値を使用して<see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" />だけが最初にアセンブリでは、同じプロバイダーが使用するまで 1 回とためプロバイダー参照が行わします。
                </para>
      <para>
                この属性は、次の順序で調べ: <list type="number"> <item>エントリで<see cref="T:System.Reflection.Assembly" />メソッドを呼び出すことによって取得<see cref="M:System.Reflection.Assembly.GetEntryAssembly" /> </item> <item>で、<see cref="T:System.Reflection.Assembly" />をリモートのインターフェイスを定義します。リスナーまたはプロキシを作成しています。</item></list></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ActorRemotingProviderAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
                <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactory">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory(class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.CreateServiceRemotingClientFactory(Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateServiceRemotingClientFactory (callbackClient As IServiceRemotingCallbackClient) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" Usage="actorRemotingProviderAttribute.CreateServiceRemotingClientFactory callbackClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackClient" Type="Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient" />
      </Parameters>
      <Docs>
        <param name="callbackClient">
                クライアントの実装がコールバックをディスパッチする必要があります。
            </param>
        <summary>
                リモートのアクター インターフェイスに接続されているサービスのリモート処理クライアント ファクトリを作成します。
            </summary>
        <returns>
                <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />で使用できる<see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" />リモート アクター インターフェイス上で、アクターと対話するアクターのプロキシを生成します。
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactoryV2">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2 (Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2(class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2(Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateServiceRemotingClientFactoryV2 (callbackMessageHandler As IServiceRemotingCallbackMessageHandler) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingClientFactoryV2 : Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" Usage="actorRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2 callbackMessageHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
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
            使用できるサービスのリモート処理クライアント ファクトリを作成、<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" />サービスのリモート インターフェイスのプロキシを作成します。
            </summary>
        <returns><see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.CreateServiceRemotingListener(Microsoft.ServiceFabric.Actors.Runtime.ActorService)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingListener : Microsoft.ServiceFabric.Actors.Runtime.ActorService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="actorRemotingProviderAttribute.CreateServiceRemotingListener actorService" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorService" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorService" />
      </Parameters>
      <Docs>
        <param name="actorService">
                リモート処理は実行する必要があるインターフェイスがアクターをホストするアクター サービスの実装です。
                </param>
        <summary>
                リモート処理用のサービスのリモート処理リスナー アクター インターフェイスを作成します。
            </summary>
        <returns>
                <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />指定されたアクター サービス用です。
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListenerV2">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2 (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.CreateServiceRemotingListenerV2(Microsoft.ServiceFabric.Actors.Runtime.ActorService)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingListenerV2 : Microsoft.ServiceFabric.Actors.Runtime.ActorService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="actorRemotingProviderAttribute.CreateServiceRemotingListenerV2 actorService" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorService" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorService" />
      </Parameters>
      <Docs>
        <param name="actorService">
                リモート処理は実行する必要があるインターフェイスがアクターをホストするアクター サービスの実装です。
                </param>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.RemotingClient" />
      <MemberSignature Language="VB.NET" Value="Public Property RemotingClient As RemotingClient" />
      <MemberSignature Language="F#" Value="member this.RemotingClient : Microsoft.ServiceFabric.Services.Remoting.RemotingClient with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.RemotingClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.RemotingListener" />
      <MemberSignature Language="VB.NET" Value="Public Property RemotingListener As RemotingListener" />
      <MemberSignature Language="F#" Value="member this.RemotingListener : Microsoft.ServiceFabric.Services.Remoting.RemotingListener with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.RemotingListener" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
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