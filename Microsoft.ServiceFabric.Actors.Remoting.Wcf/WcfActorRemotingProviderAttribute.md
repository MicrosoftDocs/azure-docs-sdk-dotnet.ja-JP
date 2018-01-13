<Type Name="WcfActorRemotingProviderAttribute" FullName="Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute">
  <TypeSignature Language="C#" Value="public sealed class WcfActorRemotingProviderAttribute : Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit WcfActorRemotingProviderAttribute extends Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class WcfActorRemotingProviderAttribute&#xA;Inherits ActorRemotingProviderAttribute" />
  <TypeSignature Language="F#" Value="type WcfActorRemotingProviderAttribute = class&#xA;    inherit ActorRemotingProviderAttribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.AttributeUsage(System.AttributeTargets.Assembly)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
                リモート処理の既定のプロバイダーとしてのアクターの WCF を設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfActorRemotingProviderAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            作成、<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute" />これは、アクターのリモート処理の既定のプロバイダーとしての WCF の設定を使用できます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseTimeoutInMilliSeconds">
      <MemberSignature Language="C#" Value="public long CloseTimeoutInMilliSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CloseTimeoutInMilliSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.CloseTimeoutInMilliSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property CloseTimeoutInMilliSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.CloseTimeoutInMilliSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.CloseTimeoutInMilliSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                取得または (ミリ秒) のメッセージ、接続を中止する前に、接続のドレインを待機する時間を設定します。 
            </summary>
        <value>
                (ミリ秒) のメッセージ、接続を中止する前に、接続のドレインを待機する時間です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactory">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory(class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.CreateServiceRemotingClientFactory(Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactory (callbackClient As IServiceRemotingCallbackClient) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" Usage="wcfActorRemotingProviderAttribute.CreateServiceRemotingClientFactory callbackClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
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
                リモートのアクター インターフェイスへの接続にサービスのリモート処理クライアント ファクトリを作成します。
            </summary>
        <returns>
                A<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Wcf.Client.WcfActorRemotingClientFactory" />として<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />で使用できる<see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" />リモート アクター インターフェイス上で、アクターと対話するアクターのプロキシを生成します。
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactoryV2">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2 (Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2(class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2(Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactoryV2 (callbackMessageHandler As IServiceRemotingCallbackMessageHandler) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactoryV2 : Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" Usage="wcfActorRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2 callbackMessageHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackMessageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler" />
      </Parameters>
      <Docs>
        <param name="callbackMessageHandler">
                クライアントの実装がコールバックをディスパッチする必要があります。
            </param>
        <summary>
                リモート アクター インターフェイスへの接続に V2 サービス リモート処理クライアント ファクトリを作成します。
            </summary>
        <returns>
                A<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Wcf.Client.WcfActorRemotingClientFactory" />として<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" />で使用できる<see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" />リモート アクター インターフェイス上で、アクターと対話するアクターのプロキシを生成します。
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.CreateServiceRemotingListener(Microsoft.ServiceFabric.Actors.Runtime.ActorService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListener : Microsoft.ServiceFabric.Actors.Runtime.ActorService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="wcfActorRemotingProviderAttribute.CreateServiceRemotingListener actorService" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
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
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2 (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.CreateServiceRemotingListenerV2(Microsoft.ServiceFabric.Actors.Runtime.ActorService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListenerV2 : Microsoft.ServiceFabric.Actors.Runtime.ActorService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="wcfActorRemotingProviderAttribute.CreateServiceRemotingListenerV2 actorService" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
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
                リモート処理の V2 サービス リモート処理リスナー アクター インターフェイスを作成します。
            </summary>
        <returns>
                <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />指定されたアクター サービス用です。
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMessageSize">
      <MemberSignature Language="C#" Value="public long MaxMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.MaxMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMessageSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.MaxMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリモート処理のメッセージの最大サイズをバイト単位で設定します。
            このプロパティの値が指定されていないかである場合より小さいまたは 4,194,304 バイト (4 MB) の既定値の 0 に equals を使用します。
            </summary>
        <value>
                バイト単位でリモート処理のメッセージの最大サイズ。 この値が指定されていないかである場合より小さいまたは 4,194,304 バイト (4 MB) の既定値の 0 に equals を使用します。
                </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenTimeoutInMilliSeconds">
      <MemberSignature Language="C#" Value="public long OpenTimeoutInMilliSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 OpenTimeoutInMilliSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.OpenTimeoutInMilliSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property OpenTimeoutInMilliSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.OpenTimeoutInMilliSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.Wcf.WcfActorRemotingProviderAttribute.OpenTimeoutInMilliSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                取得または接続を開く (ミリ秒) 待機する時間を設定します。
            </summary>
        <value>
                接続を開く (ミリ秒) 待機する時間です。 この値が指定されていないか、それが 0 より小さい、5000 ミリ秒の既定値が使用されます。
                </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>