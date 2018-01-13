<Type Name="StatelessService" FullName="Microsoft.ServiceFabric.Services.Runtime.StatelessService">
  <TypeSignature Language="C#" Value="public abstract class StatelessService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit StatelessService extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Runtime.StatelessService" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class StatelessService" />
  <TypeSignature Language="F#" Value="type StatelessService = class&#xA;    interface IStatelessUserServiceInstance" />
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
            ステートレス リライアブル サービス基本クラスを表す Microsoft Service Fabric に基づいています。 Microsoft Service Fabric が基づくステートレス リライアブル サービスを実装するには、このクラスから派生します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected StatelessService (System.Fabric.StatelessServiceContext serviceContext);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.StatelessServiceContext serviceContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.#ctor(System.Fabric.StatelessServiceContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (serviceContext As StatelessServiceContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Runtime.StatelessService : System.Fabric.StatelessServiceContext -&gt; Microsoft.ServiceFabric.Services.Runtime.StatelessService" Usage="new Microsoft.ServiceFabric.Services.Runtime.StatelessService serviceContext" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.StatelessServiceContext" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
            A<see cref="T:System.Fabric.StatelessServiceContext" />サービス コンテキストをについて説明します。
            </param>
        <summary>
            新しい <see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatelessService" /> のインスタンスを作成します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException" />
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public System.Fabric.StatelessServiceContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.StatelessServiceContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Runtime.StatelessService.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As StatelessServiceContext" />
      <MemberSignature Language="F#" Value="member this.Context : System.Fabric.StatelessServiceContext" Usage="Microsoft.ServiceFabric.Services.Runtime.StatelessService.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.StatelessServiceContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このステートレス サービスが動作しているサービス コンテキストを取得します。 InstanceId、PartitionId ServiceName などのような情報を提供します。
            </summary>
        <value>
            A<see cref="T:System.Fabric.StatelessServiceContext" />サービス コンテキストをについて説明します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceInstanceListeners">
      <MemberSignature Language="C#" Value="protected virtual System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt; CreateServiceInstanceListeners ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt; CreateServiceInstanceListeners() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.CreateServiceInstanceListeners" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function CreateServiceInstanceListeners () As IEnumerable(Of ServiceInstanceListener)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceInstanceListeners : unit -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt;&#xA;override this.CreateServiceInstanceListeners : unit -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt;" Usage="statelessService.CreateServiceInstanceListeners " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.CreateServiceInstanceListeners</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            サービス インスタンスの通信リスナーを指定するには、このメソッドをオーバーライドします。 通信リスナーのによって返されるエンドポイントが ListenerName の JSON 文字列として格納されているなどの文字列のエンドポイントのペア {「エンドポイント」: {"Listener1":"Endpoint1"、"Listener2":"Endpoint2"...}}
            <para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <returns>ServiceInstanceListeners の一覧</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAddresses">
      <MemberSignature Language="C#" Value="protected System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt; GetAddresses ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt; GetAddresses() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.GetAddresses" />
      <MemberSignature Language="VB.NET" Value="Protected Function GetAddresses () As IReadOnlyDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.GetAddresses : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, string&gt;" Usage="statelessService.GetAddresses " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            すべてのアドレスの一覧のこのサービス インスタンスとして取得 (ListenerName、エンドポイント) キーと値のペア。
            </summary>
        <returns>
            <see cref="T:System.Collections.Generic.IReadOnlyDictionary`2" /> (ListenerName、エンドポイント) とアドレスの一覧を含むキーと値のペア。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected virtual void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="abstract member OnAbort : unit -&gt; unit&#xA;override this.OnAbort : unit -&gt; unit" Usage="statelessService.OnAbort " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.OnAbort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            通知サービスを中止しています。  RunAsync は、取り消し処理は中止パスには待機されなかったとして、このメソッドの実行と同時に実行可能性があります。
            <para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnCloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.OnCloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statelessService.OnCloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.OnCloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">キャンセル要求を監視する指定されたキャンセル トークン。</param>
        <summary>
            サービスを閉じるための最後の手順として、このメソッドが呼び出されます。
            このインスタンスの内部コンポーネントの終了が完了したことを通知するには、このメソッドをオーバーライドします。
            <para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnOpenAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnOpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnOpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.OnOpenAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnOpenAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnOpenAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statelessService.OnOpenAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.OnOpenAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">キャンセル要求を監視するキャンセル トークン。</param>
        <summary>
            このメソッドは、サービスを開くの最後の手順として呼び出されます。
            このインスタンスの内部コンポーネントのオープンが完了したことを通知するには、このメソッドをオーバーライドします。
            <para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Partition">
      <MemberSignature Language="C#" Value="protected System.Fabric.IStatelessServicePartition Partition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.IStatelessServicePartition Partition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Runtime.StatelessService.Partition" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property Partition As IStatelessServicePartition" />
      <MemberSignature Language="F#" Value="member this.Partition : System.Fabric.IStatelessServicePartition" Usage="Microsoft.ServiceFabric.Services.Runtime.StatelessService.Partition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IStatelessServicePartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービスを現在のサービス インスタンスが属するパーティションをします。 
            </summary>
        <value>
            <see cref="T:System.Fabric.IStatelessServicePartition" />を表す、このサービス レプリカが属しているパーティション。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task RunAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task RunAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RunAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RunAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statelessService.RunAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.RunAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">キャンセル要求を監視するキャンセル トークン。</param>
        <summary>
            サービスが、サービスが表示されたら、動作するバック グラウンド タスクを実装するには、ロジックでこのメソッドをオーバーライドする必要があります。
            <para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。
            </returns>
        <remarks>
            オーバーライドする場合は、これらのガイドラインに従うようにしてください<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />: <list type="bullet"> <item> <description>確認<paramref name="cancellationToken" />に渡される<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />が実行と通知を受けた、1 回<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />として適切に終了します。できるだけ早くです。場合に注意してください<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />、目的の操作が完了を待つ必要はありません<paramref name="cancellationToken" />シグナル状態になる正常に返すことができます。</description></item><item><description>Service Fabric ランタイムがエスケープからすべての例外を処理しない<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />です。未処理の例外をからエスケープする場合<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />、Service Fabric ランタイムには、次のアクション、: <list type="bullet"> <item> <description>場合、 <see cref="T:System.Fabric.FabricException" /> (またはその派生例外のいずれか) からエスケープ<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />、Service Fabricランタイムは、このサービス インスタンスをドロップして、新しいインスタンスが作成されます。ヘルスの警告は、未処理の例外に関する詳細を含む Service Fabric Explorer に表示されます。</description></item><item><description>場合、<see cref="T:System.OperationCanceledException" />からエスケープ<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />Service Fabric ランタイムは、通知することによって取り消しを要求しましたが、<paramref name="cancellationToken" />に渡される<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />、Service Fabric ランタイムは、この例外を処理し、として正常に完了であると判断<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />.</description></item><item><description>場合、<see cref="T:System.OperationCanceledException" />からエスケープ<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />Service Fabric ランタイムに通知することによって取り消しを要求されません<paramref name="cancellationToken" />に渡される<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />、このサービス インスタンスをホストしているプロセスが終了します。これは、同じプロセスでホストされているその他のすべてのサービス インスタンスに影響します。未処理の例外に関する詳細な情報は、Windows イベント ビューアーで表示できます。</description></item><item><description>その他の種類の例外をからエスケープする場合<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />このサービス インスタンスをホストしているプロセスが終了し、します。これは、同じプロセスでホストされているその他のすべてのサービス インスタンスに影響します。未処理の例外に関する詳細な情報は、Windows イベント ビューアーで表示できます。</description></item></list></description></item></list><para>準拠するように失敗しているこれらのガイドラインにフェールオーバー、再構成またはスタックを取得するようにサービスのアップグレードが発生することができ、サービスの可用性に影響を与えることができます。</para></remarks>
      </Docs>
    </Member>
  </Members>
</Type>