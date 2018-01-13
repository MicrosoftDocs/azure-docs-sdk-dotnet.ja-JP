<Type Name="FabricTransportServiceRemotingProviderAttribute" FullName="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute">
  <TypeSignature Language="C#" Value="public class FabricTransportServiceRemotingProviderAttribute : Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportServiceRemotingProviderAttribute extends Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportServiceRemotingProviderAttribute&#xA;Inherits ServiceRemotingProviderAttribute" />
  <TypeSignature Language="F#" Value="type FabricTransportServiceRemotingProviderAttribute = class&#xA;    inherit ServiceRemotingProviderAttribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             既定のサービスのリモート処理トランスポート プロバイダーとして、アセンブリ内のファブリック TCP トランスポートを設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingProviderAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            構築、<see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute" />これは、既定のサービスのリモート処理トランスポート プロバイダーとして、アセンブリ内のファブリック TCP トランスポートの設定を使用できます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectTimeoutInMilliseconds">
      <MemberSignature Language="C#" Value="public long ConnectTimeoutInMilliseconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ConnectTimeoutInMilliseconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.ConnectTimeoutInMilliseconds" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectTimeoutInMilliseconds As Long" />
      <MemberSignature Language="F#" Value="member this.ConnectTimeoutInMilliseconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.ConnectTimeoutInMilliseconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                取得またはミリ秒単位で接続タイムアウトを設定します。 この設定は、接続を確立する許可された最大時間を指定します。
                </summary>
        <value>
                ミリ秒単位で接続タイムアウト。
            </value>
        <remarks>ConnectTimeout タイムアウトの既定値は、5 秒です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactory">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory(class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingClientFactory(Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactory (callbackClient As IServiceRemotingCallbackClient) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" Usage="fabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingClientFactory callbackClient" />
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
        <param name="callbackClient">
               コールバックをディスパッチする必要があるクライアントの実装です。
            </param>
        <summary>
                リモート サービス インターフェイスを介してサービスに接続の V1 サービス リモート処理クライアント ファクトリを作成します。
            </summary>
        <returns>
                A<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" />として<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />で使用できる<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" />リモート アクター インターフェイス上でステートレスまたはステートフルなサービスと対話するサービスのプロキシを生成します。
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactoryV2">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2 (Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2(class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2(Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactoryV2 (callbackMessageHandler As IServiceRemotingCallbackMessageHandler) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactoryV2 : Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" Usage="fabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2 callbackMessageHandler" />
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
        <param name="callbackMessageHandler">
               コールバックをディスパッチする必要があるクライアントの実装です。
            </param>
        <summary>
                リモート サービス インターフェイスを介してサービスに接続の V2 サービス リモート処理クライアント ファクトリを作成します。
            </summary>
        <returns>
                A<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" />として<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" />で使用できる<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" />リモート アクター インターフェイス上でステートレスまたはステートフルなサービスと対話するサービスのプロキシを生成します。
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingListener(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="fabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingListener (serviceContext, serviceImplementation)" />
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
        <param name="serviceContext">
                リモート処理のリスナーが構築される、サービスのコンテキスト。
            </param>
        <param name="serviceImplementation">
                サービス実装オブジェクト。
            </param>
        <summary>
                リモート処理用のサービスのリモート処理リスナーをサービス インターフェイスを作成します。
            </summary>
        <returns>
                A<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" />として<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />の指定されたサービスの実装です。
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListenerV2">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2 (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingListenerV2(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListenerV2 : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="fabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingListenerV2 (serviceContext, serviceImplementation)" />
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
        <param name="serviceContext">
                リモート処理のリスナーが構築される、サービスのコンテキスト。
            </param>
        <param name="serviceImplementation">
                サービス実装オブジェクト。
            </param>
        <summary>
                リモート処理サービス インターフェイスの V2 サービス リモート処理リスナーを作成します。
            </summary>
        <returns>
                A<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" />として<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />の指定されたサービスの実装です。
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAliveTimeoutInSeconds">
      <MemberSignature Language="C#" Value="public long KeepAliveTimeoutInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 KeepAliveTimeoutInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.KeepAliveTimeoutInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAliveTimeoutInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.KeepAliveTimeoutInSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.KeepAliveTimeoutInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                取得またはキープ アライブ タイムアウトを秒単位で設定します。 この設定は、クライアントとサービスがしばらくアイドル状態がある場合、接続を閉じているロード バランサーを使用して接続しているときシナリオで役立ちます。
                かどうかキープ アライブ タイムアウトが構成されている、接続が維持されるその間隔で ping メッセージを送信しています。
                </summary>
        <value>
                秒単位でキープ アライブ タイムアウト。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMessageSize">
      <MemberSignature Language="C#" Value="public long MaxMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.MaxMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMessageSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.MaxMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
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
    <Member MemberName="OperationTimeoutInSeconds">
      <MemberSignature Language="C#" Value="public long OperationTimeoutInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 OperationTimeoutInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.OperationTimeoutInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeoutInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.OperationTimeoutInSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.OperationTimeoutInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                取得または操作のタイムアウトを秒単位で設定します。 指定された時間で操作が完了していない場合それがタイムアウトします。既定では、例外ハンドラーの<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" />例外を定期的に再試行します。 お勧めを変更する操作のタイムアウトの既定値からします。 
                </summary>
        <value>
                操作のタイムアウト (秒)。 指定またはしていない場合、既定の操作よりも小さいタイムアウトの最大値を使用します。 
                </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>