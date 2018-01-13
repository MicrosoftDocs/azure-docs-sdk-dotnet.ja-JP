<Type Name="StatefulServiceBase" FullName="Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase">
  <TypeSignature Language="C#" Value="public abstract class StatefulServiceBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit StatefulServiceBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class StatefulServiceBase" />
  <TypeSignature Language="F#" Value="type StatefulServiceBase = class&#xA;    interface IStatefulUserServiceReplica" />
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
            Microsoft Service Fabric が基づくステートフルな信頼性の高いサービスの基本クラスを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected StatefulServiceBase (System.Fabric.StatefulServiceContext serviceContext, Microsoft.ServiceFabric.Data.IStateProviderReplica2 stateProviderReplica);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.StatefulServiceContext serviceContext, class Microsoft.ServiceFabric.Data.IStateProviderReplica2 stateProviderReplica) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.#ctor(System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Data.IStateProviderReplica2)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (serviceContext As StatefulServiceContext, stateProviderReplica As IStateProviderReplica2)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase : System.Fabric.StatefulServiceContext * Microsoft.ServiceFabric.Data.IStateProviderReplica2 -&gt; Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" Usage="new Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase (serviceContext, stateProviderReplica)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.StatefulServiceContext" />
        <Parameter Name="stateProviderReplica" Type="Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
            A<see cref="T:System.Fabric.StatefulServiceContext" />レプリカ ID、パーティション ID、およびサービスの名前などの情報を提供するサービス コンテキストについて説明します。
            </param>
        <param name="stateProviderReplica">
            A<see cref="T:Microsoft.ServiceFabric.Data.IStateProviderReplica2" />信頼性の高い状態プロバイダーの複製を表します。
            </param>
        <summary>
            新しいステートフルなサービスを作成します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException" />
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (Microsoft.ServiceFabric.Data.BackupDescription backupDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task BackupAsync(valuetype Microsoft.ServiceFabric.Data.BackupDescription backupDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.BackupAsync(Microsoft.ServiceFabric.Data.BackupDescription)" />
      <MemberSignature Language="F#" Value="member this.BackupAsync : Microsoft.ServiceFabric.Data.BackupDescription -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.BackupAsync backupDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDescription" Type="Microsoft.ServiceFabric.Data.BackupDescription" />
      </Parameters>
      <Docs>
        <param name="backupDescription">
            A<see cref="T:Microsoft.ServiceFabric.Data.BackupDescription" />バックアップ要求を記述します。
            </param>
        <summary>
            これによって管理されるすべての信頼性の高い状態のバックアップを実行<see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />です。
            </summary>
        <returns>非同期のバックアップ操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (Microsoft.ServiceFabric.Data.BackupDescription backupDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task BackupAsync(valuetype Microsoft.ServiceFabric.Data.BackupDescription backupDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.BackupAsync(Microsoft.ServiceFabric.Data.BackupDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.BackupAsync : Microsoft.ServiceFabric.Data.BackupDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.BackupAsync (backupDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDescription" Type="Microsoft.ServiceFabric.Data.BackupDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupDescription">A<see cref="T:Microsoft.ServiceFabric.Data.BackupDescription" />バックアップ要求を記述します。</param>
        <param name="timeout">この操作のタイムアウト。</param>
        <param name="cancellationToken">キャンセル トークンを使用して、キャンセル要求を監視します。</param>
        <summary>
            これによって管理されるすべての信頼性の高い状態のバックアップを実行<see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />です。
            </summary>
        <returns>非同期のバックアップ操作を表すタスク。</returns>
        <remarks>
            BackupCallback によって返されるブール値では、サービスが正常に外部の場所に、バックアップ フォルダーを移動するかどうかを示します。
            False が返される場合は BackupAsync backupCallback false が返されたことを示す関連するメッセージに InvalidOperationException がスローされます。
            また、バックアップはマークされます失敗とします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public System.Fabric.StatefulServiceContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.StatefulServiceContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As StatefulServiceContext" />
      <MemberSignature Language="F#" Value="member this.Context : System.Fabric.StatefulServiceContext" Usage="Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.StatefulServiceContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このステートフル サービスが動作しているサービス コンテキストを取得します。
            レプリカ ID、パーティション ID、サービス名などのような情報を提供します。
            </summary>
        <value>
            A<see cref="T:System.Fabric.StatefulServiceContext" />レプリカ ID、パーティション ID、およびサービスの名前などの情報を提供するサービス コンテキストについて説明します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceReplicaListeners">
      <MemberSignature Language="C#" Value="protected virtual System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt; CreateServiceReplicaListeners ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt; CreateServiceReplicaListeners() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.CreateServiceReplicaListeners" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function CreateServiceReplicaListeners () As IEnumerable(Of ServiceReplicaListener)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceReplicaListeners : unit -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt;&#xA;override this.CreateServiceReplicaListeners : unit -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt;" Usage="statefulServiceBase.CreateServiceReplicaListeners " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.CreateServiceReplicaListeners</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            サービス レプリカの通信リスナーを指定するには、このメソッドをオーバーライドします。 通信リスナーによって返されるエンドポイントは、格納されている ListenerName の JSON 文字列としてのようなエンドポイントの文字列のペア 
            <code>{"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</code><para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <returns>一覧<see cref="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener" /></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAddresses">
      <MemberSignature Language="C#" Value="protected System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt; GetAddresses ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt; GetAddresses() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.GetAddresses" />
      <MemberSignature Language="VB.NET" Value="Protected Function GetAddresses () As IReadOnlyDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.GetAddresses : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, string&gt;" Usage="statefulServiceBase.GetAddresses " />
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
            すべてのアドレスの一覧のこのサービス レプリカとして取得 (ListenerName、エンドポイント) キーと値のペア。
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="abstract member OnAbort : unit -&gt; unit&#xA;override this.OnAbort : unit -&gt; unit" Usage="statefulServiceBase.OnAbort " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.OnAbort</InterfaceMember>
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
            サービスを中止中の通知です。 RunAsync は、取り消し処理は中止パスには待機されなかったとして、このメソッドの実行と同時に実行可能性があります。 
            <para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnChangeRoleAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.OnChangeRoleAsync (newRole, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole">新しい<see cref="T:System.Fabric.ReplicaRole" />このサービス レプリカにします。</param>
        <param name="cancellationToken">キャンセル要求を監視するキャンセル トークン。</param>
        <summary>
            レプリカのロールを変更すると、最後の手順を完了する前に、このメソッドが呼び出されます<see cref="M:System.Fabric.IStatefulServiceReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />です。
            このレプリカの内部コンポーネントの ChangeRole が完了したことを通知するには、このメソッドをオーバーライドします。
            <para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task" />未処理の操作を表すです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnCloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnCloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.OnCloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.OnCloseAsync(System.Threading.CancellationToken)</InterfaceMember>
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
            サービスを正常に閉じるための最後の手順として、このメソッドが呼び出されます。
            このレプリカの内部コンポーネントの終了が完了したことを通知するには、このメソッドをオーバーライドします。
            <para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;bool&gt; OnDataLossAsync (Microsoft.ServiceFabric.Data.RestoreContext restoreCtx, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; OnDataLossAsync(valuetype Microsoft.ServiceFabric.Data.RestoreContext restoreCtx, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnDataLossAsync(Microsoft.ServiceFabric.Data.RestoreContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnDataLossAsync : Microsoft.ServiceFabric.Data.RestoreContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.OnDataLossAsync : Microsoft.ServiceFabric.Data.RestoreContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="statefulServiceBase.OnDataLossAsync (restoreCtx, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restoreCtx" Type="Microsoft.ServiceFabric.Data.RestoreContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="restoreCtx">
            A<see cref="T:Microsoft.ServiceFabric.Data.RestoreContext" />サービスを復元するために使用します。
            </param>
        <param name="cancellationToken">
          <see cref="T:System.Threading.CancellationToken" />キャンセル要求を監視します。
            </param>
        <summary>
            このメソッドは、疑いのあるデータの消失時に呼び出されます。 データの損失が発生した場合、サービスを復元するには、このメソッドをオーバーライドすることができます。
            </summary>
        <returns>
            非同期の復元操作を表すタスク。
            True は、状態が復元されていることを示します。
            False は、レプリカの状態が変更されていないことを示します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnOpenAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnOpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnOpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnOpenAsync(System.Fabric.ReplicaOpenMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnOpenAsync : System.Fabric.ReplicaOpenMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnOpenAsync : System.Fabric.ReplicaOpenMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.OnOpenAsync (openMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.OnOpenAsync(System.Fabric.ReplicaOpenMode,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="openMode" Type="System.Fabric.ReplicaOpenMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="openMode">
          <see cref="T:System.Fabric.ReplicaOpenMode" />このサービス レプリカです。</param>
        <param name="cancellationToken">キャンセル要求を監視するキャンセル トークン。</param>
        <summary>
            レプリカが開かれると、サービスを開くの最後の手順は、このメソッドが呼び出されます。
            このレプリカの内部コンポーネントのオープンが完了したことを通知するには、このメソッドをオーバーライドします。
            <para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRestoreCompletedAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnRestoreCompletedAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnRestoreCompletedAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnRestoreCompletedAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnRestoreCompletedAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnRestoreCompletedAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.OnRestoreCompletedAsync cancellationToken" />
      <MemberType>Method</MemberType>
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
        <param name="cancellationToken">
          <see cref="T:System.Threading.CancellationToken" />キャンセル要求を監視します。
            </param>
        <summary>
            バックアップの復元サービスを経由してレプリカの状態が正常に復元された場合、このメソッドが呼び出されます
            </summary>
        <returns>
            非同期操作を表すタスク。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Partition">
      <MemberSignature Language="C#" Value="protected System.Fabric.IStatefulServicePartition Partition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.IStatefulServicePartition Partition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.Partition" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property Partition As IStatefulServicePartition" />
      <MemberSignature Language="F#" Value="member this.Partition : System.Fabric.IStatefulServicePartition" Usage="Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.Partition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IStatefulServicePartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            レプリカを現在のサービスが属するサービス パーティション。 
            </summary>
        <value>
            <see cref="T:System.Fabric.IStatefulServicePartition" />を表す、このサービス レプリカが属しているパーティション。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task RunAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task RunAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RunAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RunAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.RunAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.RunAsync(System.Threading.CancellationToken)</InterfaceMember>
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
            このメソッドは、処理ループとして実装され、レプリカがプライマリの書き込みの状態の場合にのみ呼び出すことができます。
            アプリケーションのロジックでこのメソッドをオーバーライドします。 
            <para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。
            </returns>
        <remarks>
            オーバーライドする場合は、これらのガイドラインに従うようにしてください<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />: <list type="bullet"> <item> <description>確認<paramref name="cancellationToken" />に渡される<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />が実行と通知を受けた、1 回<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />として適切に終了します。できるだけ早くです。場合に注意してください<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />、目的の操作が完了を待つ必要はありません<paramref name="cancellationToken" />シグナル状態になる正常に返すことができます。</description></item><item><description>Service Fabric ランタイムがエスケープからすべての例外を処理しない<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />です。未処理の例外をからエスケープする場合<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />、Service Fabric ランタイムには、次のアクション、: <list type="bullet"> <item> <description>場合、 <see cref="T:System.Fabric.FabricException" /> (またはその派生例外のいずれか) からエスケープ<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />、Service Fabric実行時に、このサービス レプリカが再起動します。ヘルスの警告は、未処理の例外に関する詳細を含む Service Fabric Explorer に表示されます。</description></item><item><description>場合、<see cref="T:System.OperationCanceledException" />からエスケープ<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />Service Fabric ランタイムは、通知することによって取り消しを要求しましたが、<paramref name="cancellationToken" />に渡される<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />、Service Fabric ランタイムは、この例外を処理し、として正常に完了であると判断<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />.</description></item><item><description>場合、<see cref="T:System.OperationCanceledException" />からエスケープ<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />Service Fabric ランタイムに通知することによって取り消しを要求されません<paramref name="cancellationToken" />に渡される<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />、このサービスのレプリカをホストしているプロセスが終了します。これは、同じプロセスでホストされているその他のすべてのサービス レプリカに影響します。未処理の例外に関する詳細な情報は、Windows イベント ビューアーで表示できます。</description></item><item><description>その他の種類の例外をからエスケープする場合<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />このサービスのレプリカをホストしているプロセスが終了し、します。これは、同じプロセスでホストされているその他のすべてのサービス レプリカに影響します。未処理の例外に関する詳細な情報は、Windows イベント ビューアーで表示できます。</description></item></list></description></item></list><para>準拠するように失敗しているこれらのガイドラインにフェールオーバー、再構成またはスタックを取得するようにサービスのアップグレードが発生することができ、サービスの可用性に影響を与えることができます。</para></remarks>
      </Docs>
    </Member>
  </Members>
</Type>