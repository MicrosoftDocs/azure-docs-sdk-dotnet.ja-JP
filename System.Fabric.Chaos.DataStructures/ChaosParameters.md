<Type Name="ChaosParameters" FullName="System.Fabric.Chaos.DataStructures.ChaosParameters">
  <TypeSignature Language="C#" Value="public class ChaosParameters : System.Fabric.ByteSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit ChaosParameters extends System.Fabric.ByteSerializable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Chaos.DataStructures.ChaosParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ChaosParameters&#xA;Inherits ByteSerializable" />
  <TypeSignature Language="F#" Value="type ChaosParameters = class&#xA;    inherit ByteSerializable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.ByteSerializable</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            このクラスは、ChaosTestScenario を構成するすべてのテスト パラメーターを定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <returns>ChaosScenarioParameters として型指定された Chaos シナリオのパラメーターを格納するオブジェクト</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosParameters (long maxConcurrentFaults, Nullable&lt;TimeSpan&gt; timeToRun = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 maxConcurrentFaults, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeToRun) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.#ctor(System.Int64,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxConcurrentFaults As Long, Optional timeToRun As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.ChaosParameters : int64 * Nullable&lt;TimeSpan&gt; -&gt; System.Fabric.Chaos.DataStructures.ChaosParameters" Usage="new System.Fabric.Chaos.DataStructures.ChaosParameters (maxConcurrentFaults, timeToRun)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxConcurrentFaults" Type="System.Int64" />
        <Parameter Name="timeToRun" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="maxConcurrentFaults">最下位のイテレーションにつき誘発される同時実行エラーの最大数は、1 をされています。 高い同時実行性、比較的余裕のないしたがってより複雑な一連のバグの発見にエラーを発生させることでフェールオーバーします。 この 2 または 3 を使用することをお勧めします。</param>
        <param name="timeToRun">時間の合計 Chaos を実行する必要があります。最大許容値は TimeSpan.FromSeconds (uint です。MaxValue)</param>
        <summary>
          <para><see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <returns>ChaosScenarioParameters として型指定された Chaos シナリオのパラメーターを格納するオブジェクト</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosParameters (TimeSpan maxClusterStabilizationTimeout, long maxConcurrentFaults, bool enableMoveReplicaFaults, Nullable&lt;TimeSpan&gt; timeToRun = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan maxClusterStabilizationTimeout, int64 maxConcurrentFaults, bool enableMoveReplicaFaults, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeToRun) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.#ctor(System.TimeSpan,System.Int64,System.Boolean,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxClusterStabilizationTimeout As TimeSpan, maxConcurrentFaults As Long, enableMoveReplicaFaults As Boolean, Optional timeToRun As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.ChaosParameters : TimeSpan * int64 * bool * Nullable&lt;TimeSpan&gt; -&gt; System.Fabric.Chaos.DataStructures.ChaosParameters" Usage="new System.Fabric.Chaos.DataStructures.ChaosParameters (maxClusterStabilizationTimeout, maxConcurrentFaults, enableMoveReplicaFaults, timeToRun)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxClusterStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="maxConcurrentFaults" Type="System.Int64" />
        <Parameter Name="enableMoveReplicaFaults" Type="System.Boolean" />
        <Parameter Name="timeToRun" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="maxClusterStabilizationTimeout">フォールトの反復処理後に安定してクラスター全体の待機する時間の最大量TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</param>
        <param name="maxConcurrentFaults">最下位のイテレーションにつき誘発される同時実行エラーの最大数は、1 をされています。 高い同時実行性、比較的余裕のないしたがってより複雑な一連のバグの発見にエラーを発生させることでフェールオーバーします。 この 2 または 3 を使用することをお勧めします。</param>
        <param name="enableMoveReplicaFaults">有効またはエラー MovePrimary と MoveSecondary を無効にします。</param>
        <param name="timeToRun">時間の合計 Chaos を実行する必要があります。最大許容値は TimeSpan.FromSeconds (uint です。MaxValue)</param>
        <summary>
          <para><see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <returns>ChaosScenarioParameters として型指定された Chaos シナリオのパラメーターを格納するオブジェクト</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosParameters (TimeSpan maxClusterStabilizationTimeout, long maxConcurrentFaults, bool enableMoveReplicaFaults, TimeSpan timeToRun, System.Collections.Generic.Dictionary&lt;string,string&gt; context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan maxClusterStabilizationTimeout, int64 maxConcurrentFaults, bool enableMoveReplicaFaults, valuetype System.TimeSpan timeToRun, class System.Collections.Generic.Dictionary`2&lt;string, string&gt; context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.#ctor(System.TimeSpan,System.Int64,System.Boolean,System.TimeSpan,System.Collections.Generic.Dictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxClusterStabilizationTimeout As TimeSpan, maxConcurrentFaults As Long, enableMoveReplicaFaults As Boolean, timeToRun As TimeSpan, context As Dictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.ChaosParameters : TimeSpan * int64 * bool * TimeSpan * System.Collections.Generic.Dictionary&lt;string, string&gt; -&gt; System.Fabric.Chaos.DataStructures.ChaosParameters" Usage="new System.Fabric.Chaos.DataStructures.ChaosParameters (maxClusterStabilizationTimeout, maxConcurrentFaults, enableMoveReplicaFaults, timeToRun, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxClusterStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="maxConcurrentFaults" Type="System.Int64" />
        <Parameter Name="enableMoveReplicaFaults" Type="System.Boolean" />
        <Parameter Name="timeToRun" Type="System.TimeSpan" />
        <Parameter Name="context" Type="System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="maxClusterStabilizationTimeout">フォールトの反復処理後に安定してクラスター全体の待機する時間の最大量TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</param>
        <param name="maxConcurrentFaults">最下位のイテレーションにつき誘発される同時実行エラーの最大数は、1 をされています。 高い同時実行性、比較的余裕のないしたがってより複雑な一連のバグの発見にエラーを発生させることでフェールオーバーします。 この 2 または 3 を使用することをお勧めします。</param>
        <param name="enableMoveReplicaFaults">有効またはエラー MovePrimary と MoveSecondary を無効にします。</param>
        <param name="timeToRun">実行後にこの時間がかかり、Chaos が停止します。TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</param>
        <param name="context">これは、(キー、値) のバッグのペア。 なぜ Chaos が起動されている例に関する詳細なコンテキストを記録するために使用できます。</param>
        <summary>
          <para><see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <returns>ChaosScenarioParameters として型指定された Chaos シナリオのパラメーターを格納するオブジェクト</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosParameters (TimeSpan maxClusterStabilizationTimeout, long maxConcurrentFaults, bool enableMoveReplicaFaults, TimeSpan timeToRun, System.Collections.Generic.Dictionary&lt;string,string&gt; context, TimeSpan waitTimeBetweenIterations, TimeSpan waitTimeBetweenFaults);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan maxClusterStabilizationTimeout, int64 maxConcurrentFaults, bool enableMoveReplicaFaults, valuetype System.TimeSpan timeToRun, class System.Collections.Generic.Dictionary`2&lt;string, string&gt; context, valuetype System.TimeSpan waitTimeBetweenIterations, valuetype System.TimeSpan waitTimeBetweenFaults) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.#ctor(System.TimeSpan,System.Int64,System.Boolean,System.TimeSpan,System.Collections.Generic.Dictionary{System.String,System.String},System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxClusterStabilizationTimeout As TimeSpan, maxConcurrentFaults As Long, enableMoveReplicaFaults As Boolean, timeToRun As TimeSpan, context As Dictionary(Of String, String), waitTimeBetweenIterations As TimeSpan, waitTimeBetweenFaults As TimeSpan)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.ChaosParameters : TimeSpan * int64 * bool * TimeSpan * System.Collections.Generic.Dictionary&lt;string, string&gt; * TimeSpan * TimeSpan -&gt; System.Fabric.Chaos.DataStructures.ChaosParameters" Usage="new System.Fabric.Chaos.DataStructures.ChaosParameters (maxClusterStabilizationTimeout, maxConcurrentFaults, enableMoveReplicaFaults, timeToRun, context, waitTimeBetweenIterations, waitTimeBetweenFaults)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxClusterStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="maxConcurrentFaults" Type="System.Int64" />
        <Parameter Name="enableMoveReplicaFaults" Type="System.Boolean" />
        <Parameter Name="timeToRun" Type="System.TimeSpan" />
        <Parameter Name="context" Type="System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="waitTimeBetweenIterations" Type="System.TimeSpan" />
        <Parameter Name="waitTimeBetweenFaults" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxClusterStabilizationTimeout">フォールトの反復処理後に安定してクラスター全体の待機する時間の最大量TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</param>
        <param name="maxConcurrentFaults">最下位のイテレーションにつき誘発される同時実行エラーの最大数は、1 をされています。 高い同時実行性、比較的余裕のないしたがってより複雑な一連のバグの発見にエラーを発生させることでフェールオーバーします。 この 2 または 3 を使用することをお勧めします。</param>
        <param name="enableMoveReplicaFaults">有効またはエラー MovePrimary と MoveSecondary を無効にします。</param>
        <param name="timeToRun">実行後にこの時間がかかり、Chaos が停止します。TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</param>
        <param name="context">これは、(キー、値) のバッグのペア。 なぜ Chaos が起動されている例に関する詳細なコンテキストを記録するために使用できます。</param>
        <param name="waitTimeBetweenIterations">これは、エラーを発生させることの 2 つの連続したイテレーション間の一時停止の量です。 複数の一時停止、小時間の経過とともにエラーの比率は、TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</param>
        <param name="waitTimeBetweenFaults">これは、詳細、一時停止、--1 つのイテレーションで 2 つの連続する障害の間の一時停止の量は低くフォールトの同時実行TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</param>
        <summary>
          <para><see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosParameters (TimeSpan maxClusterStabilizationTimeout, long maxConcurrentFaults, bool enableMoveReplicaFaults, TimeSpan timeToRun, System.Collections.Generic.Dictionary&lt;string,string&gt; context, TimeSpan waitTimeBetweenIterations, TimeSpan waitTimeBetweenFaults, System.Fabric.Health.ClusterHealthPolicy clusterHealthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan maxClusterStabilizationTimeout, int64 maxConcurrentFaults, bool enableMoveReplicaFaults, valuetype System.TimeSpan timeToRun, class System.Collections.Generic.Dictionary`2&lt;string, string&gt; context, valuetype System.TimeSpan waitTimeBetweenIterations, valuetype System.TimeSpan waitTimeBetweenFaults, class System.Fabric.Health.ClusterHealthPolicy clusterHealthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.#ctor(System.TimeSpan,System.Int64,System.Boolean,System.TimeSpan,System.Collections.Generic.Dictionary{System.String,System.String},System.TimeSpan,System.TimeSpan,System.Fabric.Health.ClusterHealthPolicy)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.ChaosParameters : TimeSpan * int64 * bool * TimeSpan * System.Collections.Generic.Dictionary&lt;string, string&gt; * TimeSpan * TimeSpan * System.Fabric.Health.ClusterHealthPolicy -&gt; System.Fabric.Chaos.DataStructures.ChaosParameters" Usage="new System.Fabric.Chaos.DataStructures.ChaosParameters (maxClusterStabilizationTimeout, maxConcurrentFaults, enableMoveReplicaFaults, timeToRun, context, waitTimeBetweenIterations, waitTimeBetweenFaults, clusterHealthPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxClusterStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="maxConcurrentFaults" Type="System.Int64" />
        <Parameter Name="enableMoveReplicaFaults" Type="System.Boolean" />
        <Parameter Name="timeToRun" Type="System.TimeSpan" />
        <Parameter Name="context" Type="System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="waitTimeBetweenIterations" Type="System.TimeSpan" />
        <Parameter Name="waitTimeBetweenFaults" Type="System.TimeSpan" />
        <Parameter Name="clusterHealthPolicy" Type="System.Fabric.Health.ClusterHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="maxClusterStabilizationTimeout">フォールトの反復処理後に安定してクラスター全体の待機する時間の最大量TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</param>
        <param name="maxConcurrentFaults">最下位のイテレーションにつき誘発される同時実行エラーの最大数は、1 をされています。 高い同時実行性、比較的余裕のないしたがってより複雑な一連のバグの発見にエラーを発生させることでフェールオーバーします。 この 2 または 3 を使用することをお勧めします。</param>
        <param name="enableMoveReplicaFaults">有効またはエラー MovePrimary と MoveSecondary を無効にします。</param>
        <param name="timeToRun">実行後にこの時間がかかり、Chaos が停止します。TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</param>
        <param name="context">これは、(キー、値) のバッグのペア。 なぜ Chaos が起動されている例に関する詳細なコンテキストを記録するために使用できます。</param>
        <param name="waitTimeBetweenIterations">これは、エラーを発生させることの 2 つの連続したイテレーション間の一時停止の量です。 複数の一時停止、小時間の経過とともにエラーの比率は、TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</param>
        <param name="waitTimeBetweenFaults">これは、詳細、一時停止、--1 つのイテレーションで 2 つの連続する障害の間の一時停止の量は低くフォールトの同時実行TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</param>
        <param name="clusterHealthPolicy">どの程度健全クラスターがあります Chaos エラーを発生させることで移動するためを決定するクラスターの正常性ポリシー。</param>
        <summary>
          <para><see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterHealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthPolicy ClusterHealthPolicy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthPolicy ClusterHealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.ClusterHealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterHealthPolicy As ClusterHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.ClusterHealthPolicy : System.Fabric.Health.ClusterHealthPolicy" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.ClusterHealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ClusterHealthPolicy では、次のエラーのセット上に移動する前に複雑さを保証するエンティティのヘルスの状態を判断します。 'ConsiderWarningAsError' を false に設定とは、healthState、クラスター内のエンティティがあるときに、次のエラーのセット上に移動 Chaos、できます (ただし、Chaos はスキップされます faultable エンティティを選択するときに警告内のエンティティ)、警告を = =。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.Dictionary&lt;string,string&gt; Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.Dictionary`2&lt;string, string&gt; Context" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As Dictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Context : System.Collections.Generic.Dictionary&lt;string, string&gt;" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            バッグを取得します (キー、値) のペアの複雑さの開始中に渡されました。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableMoveReplicaFaults">
      <MemberSignature Language="C#" Value="public bool EnableMoveReplicaFaults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableMoveReplicaFaults" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.EnableMoveReplicaFaults" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableMoveReplicaFaults As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableMoveReplicaFaults : bool with get, set" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.EnableMoveReplicaFaults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            有効またはエラー MovePrimary と MoveSecondary を無効にします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxClusterStabilizationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan MaxClusterStabilizationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxClusterStabilizationTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.MaxClusterStabilizationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxClusterStabilizationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxClusterStabilizationTimeout : TimeSpan with get, set" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.MaxClusterStabilizationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            テストが失敗する前に、エラーの後に安定してクラスターを待機する時間の最大量。
            </summary>
        <value>
            繰り返すたびに、ChaosTestScenario 待ちます多くてこの時間に異常な状態になるクラスターの数
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentFaults">
      <MemberSignature Language="C#" Value="public long MaxConcurrentFaults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxConcurrentFaults" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.MaxConcurrentFaults" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrentFaults As Long" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentFaults : int64 with get, set" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.MaxConcurrentFaults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            最下位のイテレーションにつき誘発される同時実行エラーの最大数は、1 をされています。 高い同時実行性、比較的余裕のないフェールオーバーです。したがってより複雑な連続する 2 または 3 を使用して、この - バグの発見に障害を誘導することをお勧めします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public override void Read (System.IO.BinaryReader br);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Read(class System.IO.BinaryReader br) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.Read(System.IO.BinaryReader)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Read (br As BinaryReader)" />
      <MemberSignature Language="F#" Value="override this.Read : System.IO.BinaryReader -&gt; unit" Usage="chaosParameters.Read br" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="br" Type="System.IO.BinaryReader" />
      </Parameters>
      <Docs>
        <param name="br">BinaryReader オブジェクト</param>
        <summary>
            バイト配列から、このオブジェクトの状態を読み取ります。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.IO.EndOfStreamException">ストリームの末尾に到達しました。 </exception>
        <exception cref="T:System.IO.IOException">I/O エラーが発生します。 </exception>
      </Docs>
    </Member>
    <Member MemberName="TimeToRun">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToRun { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToRun" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.TimeToRun" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeToRun As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToRun : TimeSpan" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.TimeToRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            終了する前に、シナリオを実行する時間の合計。
            </summary>
        <value>
            TimeSpan としてシナリオの最大実行時間を返します
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="chaosParameters.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            クラスの文字列表現を返します
            </summary>
        <returns>String オブジェクト</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitTimeBetweenFaults">
      <MemberSignature Language="C#" Value="public TimeSpan WaitTimeBetweenFaults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WaitTimeBetweenFaults" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.WaitTimeBetweenFaults" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitTimeBetweenFaults As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WaitTimeBetweenFaults : TimeSpan with get, set" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.WaitTimeBetweenFaults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            待機連続する障害の間の時間の上限: 値が大きいほど、低く (エラー) の同時実行します。
            </summary>
        <value>
            TimeSpan として 2 つの連続する障害の間の最大待機時間を返します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitTimeBetweenIterations">
      <MemberSignature Language="C#" Value="public TimeSpan WaitTimeBetweenIterations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WaitTimeBetweenIterations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.WaitTimeBetweenIterations" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitTimeBetweenIterations As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WaitTimeBetweenIterations : TimeSpan with get, set" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.WaitTimeBetweenIterations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この値によってバインドされるランダムな期間の 2 つのイテレーションまでの時間を待機します。
            </summary>
        <value>
            ChaosTestScenario の 2 つの連続したイテレーション間の時間の分離
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public override void Write (System.IO.BinaryWriter bw);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Write(class System.IO.BinaryWriter bw) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.Write(System.IO.BinaryWriter)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Write (bw As BinaryWriter)" />
      <MemberSignature Language="F#" Value="override this.Write : System.IO.BinaryWriter -&gt; unit" Usage="chaosParameters.Write bw" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="bw" Type="System.IO.BinaryWriter" />
      </Parameters>
      <Docs>
        <param name="bw">BinaryWriter オブジェクトです。</param>
        <summary>
            このオブジェクトの状態をバイト配列に書き込みます。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.IO.IOException">I/O エラーが発生します。 </exception>
      </Docs>
    </Member>
  </Members>
</Type>