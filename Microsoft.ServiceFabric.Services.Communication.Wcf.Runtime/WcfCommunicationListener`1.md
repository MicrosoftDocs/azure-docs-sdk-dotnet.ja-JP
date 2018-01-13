<Type Name="WcfCommunicationListener&lt;TServiceContract&gt;" FullName="Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;TServiceContract&gt;">
  <TypeSignature Language="C#" Value="public class WcfCommunicationListener&lt;TServiceContract&gt; : Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfCommunicationListener`1&lt;TServiceContract&gt; extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfCommunicationListener(Of TServiceContract)&#xA;Implements ICommunicationListener" />
  <TypeSignature Language="F#" Value="type WcfCommunicationListener&lt;'ServiceContract&gt; = class&#xA;    interface ICommunicationListener" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TServiceContract" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TServiceContract">WCF サービス コントラクトの型。</typeparam>
    <summary>
            Service Fabric 用 Windows Communication Foundation のベースのリスナーは、ステートレスまたはステートフルなサービスを基づいています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfCommunicationListener (System.Fabric.ServiceContext serviceContext, TServiceContract wcfServiceObject);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, !TServiceContract wcfServiceObject) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.#ctor(System.Fabric.ServiceContext,`0)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; : System.Fabric.ServiceContext * 'ServiceContract -&gt; Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt;" Usage="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; (serviceContext, wcfServiceObject)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="wcfServiceObject" Type="TServiceContract" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                この通信リスナーが構築される、サービスのコンテキスト。
            </param>
        <param name="wcfServiceObject">
                WCF サービスが指定された WCF サービス コントラクトを実装します。
            </param>
        <summary>
                既定のバインディングと既定のエンドポイント アドレスを使用する通信リスナーを WCF 構成要素に基づいています。
            </summary>
        <remarks>
          <para>
                    使用して、既定のリスナーのバインドを作成<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />メソッドです。
                </para>
          <para>
                    サービス マニフェストで定義されているエンドポイント リソースを使用して、既定のエンドポイント アドレスが作成されます。 エンドポイント リソースの名前は、WCF サービス コントラクトを使用して型から派生<see cref="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" />メソッドです。
                    サービス マニフェストには、エンドポイント リソースと一致することが見つかりません、ポート 0 既定エンドポイント リソースの定義が使用されます。
                    </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfCommunicationListener (System.Fabric.ServiceContext serviceContext, TServiceContract wcfServiceObject, System.ServiceModel.Channels.Binding listenerBinding = null, System.ServiceModel.EndpointAddress address = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, !TServiceContract wcfServiceObject, class System.ServiceModel.Channels.Binding listenerBinding, class System.ServiceModel.EndpointAddress address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.#ctor(System.Fabric.ServiceContext,`0,System.ServiceModel.Channels.Binding,System.ServiceModel.EndpointAddress)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; : System.Fabric.ServiceContext * 'ServiceContract * System.ServiceModel.Channels.Binding * System.ServiceModel.EndpointAddress -&gt; Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt;" Usage="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; (serviceContext, wcfServiceObject, listenerBinding, address)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="wcfServiceObject" Type="TServiceContract" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="address" Type="System.ServiceModel.EndpointAddress" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                この通信リスナーが構築される、サービスのコンテキスト。
            </param>
        <param name="wcfServiceObject">
                WCF サービスが指定された WCF サービス コントラクトを実装します。
            </param>
        <param name="listenerBinding">
                WCF エンドポイントで使用するバインディング。 使用して既定のリスナーをバインディングを作成する場合は、listenerBinding が指定されていないか、null である、<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />メソッドです。
                </param>
        <param name="address">
                WCF エンドポイントのリッスン アドレスです。 アドレスが指定されていないか、null である、既定のアドレスがサービス マニフェストのエンドポイント リソースの参照によって作成されます。 エンドポイントのリソース名は、WCF サービス コントラクトを使用して型から派生<see cref="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" />メソッドです。
                サービス マニフェストには、エンドポイント リソースと一致することが見つかりません、ポート 0 既定エンドポイント リソースの定義が使用されます。
                </param>
        <summary>
                指定されたリスナーのバインドと指定したエンドポイント アドレスから派生したエンドポイント アドレスを使用する通信リスナーを WCF 構成要素に基づいています。
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfCommunicationListener (System.Fabric.ServiceContext serviceContext, TServiceContract wcfServiceObject, System.ServiceModel.Channels.Binding listenerBinding = null, string endpointResourceName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, !TServiceContract wcfServiceObject, class System.ServiceModel.Channels.Binding listenerBinding, string endpointResourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.#ctor(System.Fabric.ServiceContext,`0,System.ServiceModel.Channels.Binding,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; : System.Fabric.ServiceContext * 'ServiceContract * System.ServiceModel.Channels.Binding * string -&gt; Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt;" Usage="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; (serviceContext, wcfServiceObject, listenerBinding, endpointResourceName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="wcfServiceObject" Type="TServiceContract" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="endpointResourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                この通信リスナーが構築される、サービスのコンテキスト。
            </param>
        <param name="wcfServiceObject">
                WCF サービスが指定された WCF サービス コントラクトを実装します。
            </param>
        <param name="listenerBinding">
                WCF エンドポイントで使用するバインディング。 使用して既定のリスナーをバインディングを作成する場合は、listenerBinding が指定されていないか、null である、<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />メソッドです。
                </param>
        <param name="endpointResourceName">
                アドレスをリスナーの作成に使用するサービス マニフェストで定義されているエンドポイント リソースの名前。 WCF サービス コントラクト型を使用して、派生した名前で、endpointResourceName が指定されていない、または null である、<see cref="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" />メソッドです。
                サービス マニフェストには、エンドポイント リソースと一致することが見つかりません、ポート 0 既定エンドポイント リソースの定義が使用されます。
                </param>
        <summary>
                指定されたリスナーのバインドと、指定したエンドポイント リソース名から派生したエンドポイント アドレスを使用する通信リスナーを WCF 構成要素に基づいています。
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort">
      <MemberSignature Language="C#" Value="void ICommunicationListener.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements ICommunicationListener.Abort" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort</InterfaceMember>
      </Implements>
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
            このメソッドによって、通信リスナーを閉じます。 閉じる終了の状態は、このメソッドは、異常終了への移行。 このメソッドが呼び出されたときに、(閉じるを含む) の未処理の操作を取り消す必要があります。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task ICommunicationListener.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1/&lt;Microsoft-ServiceFabric-Services-Communication-Runtime-ICommunicationListener-CloseAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            このメソッドによって、通信リスナーを閉じます。 終了が終了状態と、このメソッドは、安全な方法でこの状態に遷移する通信リスナーを使用します。
            </summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;string&gt; ICommunicationListener.OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#OpenAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            このメソッドによって、通信リスナーを開くことができません。 Open が完了すると、通信リスナーが使用可能になります - 受け付けるし、メッセージを送信します。
            </summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。 タスクの結果は、エンドポイントの文字列です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceHost">
      <MemberSignature Language="C#" Value="public System.ServiceModel.ServiceHost ServiceHost { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.ServiceHost ServiceHost" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.ServiceHost" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceHost As ServiceHost" />
      <MemberSignature Language="F#" Value="member this.ServiceHost : System.ServiceModel.ServiceHost" Usage="Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt;.ServiceHost" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.ServiceHost</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                取得、<see cref="T:System.ServiceModel.ServiceHost" />このリスナーで WCF サービスの実装をホストするために使用します。
                </summary>
        <value>
                A<see cref="T:System.ServiceModel.ServiceHost" />このリスナーで WCF サービスの実装をホストするために使用します。
                </value>
        <remarks>
                サービス ホストは、そのコンス トラクターでリスナーを作成します。 使用して、ランタイムによってこのような通信する前にリスナーが開かれました<see cref="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)" />メソッドでは、このプロパティを介してアクセスすると、サービス ホストをカスタマイズできます。
                </remarks>
      </Docs>
    </Member>
  </Members>
</Type>