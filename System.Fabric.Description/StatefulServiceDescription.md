<Type Name="StatefulServiceDescription" FullName="System.Fabric.Description.StatefulServiceDescription">
  <TypeSignature Language="C#" Value="public sealed class StatefulServiceDescription : System.Fabric.Description.ServiceDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatefulServiceDescription extends System.Fabric.Description.ServiceDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.StatefulServiceDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatefulServiceDescription&#xA;Inherits ServiceDescription" />
  <TypeSignature Language="F#" Value="type StatefulServiceDescription = class&#xA;    inherit ServiceDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.ServiceDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>拡張を表す<see cref="T:System.Fabric.Description.ServiceDescription" />ステートフルなサービスを作成するために必要な追加情報を提供します。</para>
    </summary>
    <remarks>
      <para />
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatefulServiceDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatefulServiceDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.StatefulServiceDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasPersistedState">
      <MemberSignature Language="C#" Value="public bool HasPersistedState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasPersistedState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.HasPersistedState" />
      <MemberSignature Language="VB.NET" Value="Public Property HasPersistedState As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasPersistedState : bool with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.HasPersistedState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはこのインスタンスの状態が永続化するかどうかを示す値を設定します。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>状態、それ以外のインスタンスが永続化する場合<languageKeyword>false</languageKeyword>です。</para>
        </value>
        <remarks>
          <para>ときに、<see cref="T:System.Fabric.FabricReplicator" />でセカンダリ レプリカが永続的なサービスの操作を受け取り、その受信確認を送信できるプライマリ前に、データが保持されていることを確認するサービスを待つ必要があります。 非永続的なサービスでは、操作受信を確認できますすぐに受信したときにします。</para>
          <para>永続的なサービスのレプリカが失敗した場合、Service Fabric すぐには考慮されませんそのレプリカを損失としてそのレプリカの永続的な状態がまだ存在するため。 レプリカを復旧した場合を再作成できます永続化された状態を使用します。 これに対し、代替レプリカをすぐにビルドを開始してがありますコストと、不要なエラーは一時的な場合は特にです。 Service Fabric が待機を最初から新しい (置換) レプリカを構築する前に回復する永続的なレプリカを構成するのには、使用、<see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />パラメーター。 非永続的なサービスの (を持つ<see cref="P:System.Fabric.Description.StatefulServiceDescription.HasPersistedState" />'éý' <languageKeyword>false</languageKeyword>)、Service Fabric の新しいレプリカの作成はすぐに開始 (から、回復する永続的な状態が存在しないためと同じようローカルな復旧を待機中にポイントがありません).</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MinReplicaSetSize">
      <MemberSignature Language="C#" Value="public int MinReplicaSetSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MinReplicaSetSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MinReplicaSetSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MinReplicaSetSize : int with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはこのサービスに許可されている最小のレプリカ セットのサイズを設定します。</para>
        </summary>
        <value>
          <para>最小値には、このサービスのレプリカ セットのサイズが許可されています。</para>
        </value>
        <remarks>
          <para>Service Fabric が、特定のパーティションのレプリカ セットのビューで保持するレプリカの最小数を定義します。 たとえば場合、<see cref="P:System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" />は 5 (5) 通常 (失敗) なし、そこに設定されて、レプリカ セットのビューに 5 つのレプリカになります。 ただし、この数は障害中に低下します。 <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />ビューでは、レプリカの最小数を定義たとえば場合、 <see cref="P:System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" /> 5 と<see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />、3 つは、3 つの同時障害 (を実行している残りの 2 つのレプリカでその結果、) 必要がありますがある場合でもレプリカ セット (を 2 とダウン) のビューに 3 つのレプリカです。 以降  
            クォーラムの過半数は、このビューで保持されるレプリカの数のマジョリティのクォーラムを使用して、<see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />は最小レベルのすべての操作の信頼性: 前の例では、ターゲット = 5 と Min = 3, 3 つの同時障害には、2 つの残りのレプリカ (および 1 つのダウン)、および 3 のマジョリティ クォーラム (、 <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />) は 2 です。 つまり、プライマリ、引き続き操作をレプリケートすること、および、進捗 (パーティション) を設定する残りのセカンダリ レプリカがレプリカの順序で操作を適用する必要があります。 レプリカの合計数を下回るマジョリティ クォーラムのかどうか、<see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />以降に書き込みを禁止する、します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="QuorumLossWaitDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; QuorumLossWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; QuorumLossWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.QuorumLossWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property QuorumLossWaitDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.QuorumLossWaitDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.QuorumLossWaitDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはクォーラム損失の状態になるパーティションが許可されている、秒単位で最大の期間を設定します。</para>
        </summary>
        <value>
          <para>この待機時間として、<see cref="T:System.TimeSpan" />オブジェクト。</para>
        </value>
        <remarks>
          <para>場合は、パーティションは、この期間が過ぎた後クォーラムが失われるは、パーティションが失われると下向きのレプリカを考慮してクォーラム損失から回復しました。 この場合、データ損失が発生する可能性があります。 既定値は無限大と、この値を変更するには使用しないでです。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaRestartWaitDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ReplicaRestartWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ReplicaRestartWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicaRestartWaitDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ReplicaRestartWaitDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定中は、レプリカがダウンしたときに、新しいレプリカが作成されたときまでの秒。</para>
        </summary>
        <value>
          <para>期間は、<see cref="T:System.TimeSpan" />オブジェクト。</para>
        </value>
        <remarks>
          <para>永続的なレプリカがダウンした場合は、このタイマーが開始されます。  有効期限が切れるときに、Service Fabric は、クラスター内の任意のノードでの新しいレプリカを作成します。 この構成では、不要な状態のコピーを減らします。 永続化されたレプリカがダウンしたときの待ち時間に戻るには、<see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />コピーが必要とする新しいレプリカを作成する前に (秒)。 注まだ、紛失、レプリカがダウンしているのとは見なされません。</para>
          <para>既定値は、300 (秒) です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StandByReplicaKeepDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; StandByReplicaKeepDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; StandByReplicaKeepDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.StandByReplicaKeepDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property StandByReplicaKeepDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StandByReplicaKeepDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.StandByReplicaKeepDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または削除されるまでの StandBy レプリカを保持する期間の定義を設定します。</para>
        </summary>
        <value>
          <para>削除されるまでの StandBy レプリカを保持する期間を定義します。</para>
        </value>
        <remarks>
          <para>レプリカをよりも長い間ダウンすると場合があります、<see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />です。 このような場合に置き換える新しいレプリカがビルドされます。 場合がありますただし、障害は永続的なと永続的なレプリカを復旧最終的にします。 これは、スタンバイ状態のレプリカを構成します。 スタンバイのレプリカは、場合はその後のエラーまたはリソースが既に存在して、回復を短縮するために使用できる永続的な状態であるため、アクションを分散優先的に使用されます。 <see cref="P:System.Fabric.Description.StatefulServiceDescription.StandByReplicaKeepDuration" />削除される前にこのような StandBy レプリカを保持する期間を定義します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetReplicaSetSize">
      <MemberSignature Language="C#" Value="public int TargetReplicaSetSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 TargetReplicaSetSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetReplicaSetSize As Integer" />
      <MemberSignature Language="F#" Value="member this.TargetReplicaSetSize : int with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> 取得またはレプリカ セットのターゲット サイズを設定します。</para>
        </summary>
        <value>
          <para>レプリカのターゲット サイズを設定します。</para>
        </value>
        <remarks>
          <para>システムを作成し、このサービスの各パーティションを保持するレプリカの数。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>