<Type Name="ReplicatorSettings" FullName="System.Fabric.ReplicatorSettings">
  <TypeSignature Language="C#" Value="public sealed class ReplicatorSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicatorSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ReplicatorSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicatorSettings" />
  <TypeSignature Language="F#" Value="type ReplicatorSettings = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>により、ステートフルなレプリカを構成するのには<see cref="T:System.Fabric.FabricReplicator" />経由での作成時に<see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicatorSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ReplicatorSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.ReplicatorSettings" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchAcknowledgementInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; BatchAcknowledgementInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; BatchAcknowledgementInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchAcknowledgementInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.BatchAcknowledgementInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" />
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
          <para>取得または受信確認を送信する前に、操作を受信した後、レプリケーターが待機する時間を設定します。 </para>
        </summary>
        <value>
          <para>受信確認を送信する前に、操作を受信した後、レプリケーターが待機する時間にバックアップします。</para>
        </value>
        <remarks>
          <para>受信し、この期間内に受信確認は、その他の操作は、1 つのメッセージで送信、受信確認があります。</para>
          <para>増加、<see cref="P:System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" />値は、各レプリケーション操作の待機時間を減らしますが、レプリケーターのスループットが向上します。</para>
          <para>既定値は、0.05 秒 (50 ミリ秒)</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialCopyQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialCopyQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialCopyQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.InitialCopyQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialCopyQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialCopyQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.InitialCopyQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定のコピー操作キュー内の初期サイズ<see cref="T:System.Fabric.FabricReplicator" />、コピーが含まれています<see cref="T:System.Fabric.IOperation" />追加されていないと、サービスによって処理されます。</para>
        </summary>
        <value>
          <para>内のコピー操作キューの初期サイズ<see cref="T:System.Fabric.FabricReplicator" />、コピーが含まれています<see cref="T:System.Fabric.IOperation" />追加されていないと、サービスによって処理されます。</para>
        </value>
        <remarks>
          <para>既定値は 64 です。 このパラメーターの値が 2 のべき乗でなければならないことに注意してください。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialPrimaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialPrimaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialPrimaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.InitialPrimaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialPrimaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialPrimaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.InitialPrimaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>プライマリ レプリケーション操作キュー内の初期サイズを定義<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />s の各単位をここでは、キューの操作の数。</para>
        </summary>
        <value>
          <para>プライマリ レプリケーション操作キュー内の初期サイズ<see cref="T:System.Fabric.FabricReplicator" /></para>
        </value>
        <remarks>
          <para>サービスのロールがプライマリである場合は、この設定は、複製物作成会社に固有</para>
          <para>既定値は 64 です。  このパラメーターの値が 2 のべき乗でなければならないことに注意してください。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.InitialReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.InitialReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはレプリケーション キューのサイズの初期サイズを設定します。</para>
        </summary>
        <value>
          <para>レプリケーション キューのサイズの初期サイズします。</para>
        </value>
        <remarks>
          <para />
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialSecondaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialSecondaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialSecondaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.InitialSecondaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialSecondaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialSecondaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.InitialSecondaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>セカンダリのレプリケーション操作キュー内の初期サイズを定義<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />s </para>
        </summary>
        <value>
          <para>内のセカンダリのレプリケーション操作キューの初期サイズ<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />追加されていないと、サービスによって処理されます。 単位をここでは、キューの操作の数 </para>
        </value>
        <remarks>
          <para>サービスの役割がセカンダリ/アイドル状態の場合は、この設定は、複製物作成会社に固有</para>
          <para>既定値は 64 です。  このパラメーターの値が 2 のべき乗でなければならないことに注意してください。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFrom">
      <MemberSignature Language="C#" Value="public static System.Fabric.ReplicatorSettings LoadFrom (System.Fabric.CodePackageActivationContext codePackageActivationContext, string configPackageName, string sectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.ReplicatorSettings LoadFrom(class System.Fabric.CodePackageActivationContext codePackageActivationContext, string configPackageName, string sectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ReplicatorSettings.LoadFrom(System.Fabric.CodePackageActivationContext,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member LoadFrom : System.Fabric.CodePackageActivationContext * string * string -&gt; System.Fabric.ReplicatorSettings" Usage="System.Fabric.ReplicatorSettings.LoadFrom (codePackageActivationContext, configPackageName, sectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicatorSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codePackageActivationContext" Type="System.Fabric.CodePackageActivationContext" />
        <Parameter Name="configPackageName" Type="System.String" />
        <Parameter Name="sectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="codePackageActivationContext">
          <para>現在のコード パッケージのアクティベーション コンテキスト<see cref="T:System.Fabric.CodePackageActivationContext" /></para>
        </param>
        <param name="configPackageName">
          <para>現在の構成パッケージ名</para>
        </param>
        <param name="sectionName">
          <para>すべての複製物作成会社設定を定義する構成ファイル内のセクション</para>
        </param>
        <summary>
          <para>読み込み、<see cref="T:System.Fabric.ReplicatorSettings" />サービス構成設定ファイルからのオブジェクト。</para>
        </summary>
        <returns>
          <para>読み込まれた<see cref="T:System.Fabric.ReplicatorSettings" />サービス構成設定ファイルからオブジェクト</para>
        </returns>
        <remarks>
          <para> サービスの構成フォルダー内の構成設定ファイル (settings.xml) には、通常を渡すために必要なすべての複製物作成会社設定が含まれています、<see cref="T:System.Fabric.ReplicatorSettings" />オブジェクトを<see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />メソッドです。 通常、負担が settings.xml ファイルを読み取り、値を解析し、適切に構築するには、サービス作成者には、<see cref="T:System.Fabric.ReplicatorSettings" />オブジェクト。</para>
          <para>現在のヘルパー メソッドを使用してサービスの作成者は、上記のプロセスをバイパスできます。</para>
          <para>サービスの構成を上記の解析中に自動的に実行する windows fabric で認識できる"settings.xml"で指定されるべきパラメーター名を次に示します。</para>
          <list type="number">
            <item>
              <description>
                <para>BatchAcknowledgementInterval –<see cref="P:System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" />値 (秒)</para>
              </description>
            </item>
            <item>
              <description>
                <para>InitialCopyQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.InitialCopyQueueSize" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>MaxCopyQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.MaxCopyQueueSize" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>MaxReplicationMessageSize-<see cref="P:System.Fabric.ReplicatorSettings.MaxReplicationMessageSize" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>RetryInterval -<see cref="P:System.Fabric.ReplicatorSettings.RetryInterval" />値 (秒)</para>
              </description>
            </item>
            <item>
              <description>
                <para>RequireServiceAck-<see cref="P:System.Fabric.ReplicatorSettings.RequireServiceAck" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>ReplicatorAddress または ReplicatorEndpoint – ReplicatorAddress IPort 形式でなければなりません。 サービス マニフェストから ReplicatorEndpoint が有効なサービス エンドポイントのリソースを参照する必要があります。<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorAddress" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>ReplicatorListenAddress または ReplicatorEndpoint – ReplicatorListenAddress IPort 形式でなければなりません。 サービス マニフェストから ReplicatorEndpoint が有効なサービス エンドポイントのリソースを参照する必要があります。<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorListenAddress" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>ReplicatorPublishAddress または ReplicatorEndpoint – ReplicatorPublishAddress IPort 形式でなければなりません。 サービス マニフェストから ReplicatorEndpoint が有効なサービス エンドポイントのリソースを参照する必要があります。<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>SecondaryClearAcknowledgedOperations-<see cref="P:System.Fabric.ReplicatorSettings.SecondaryClearAcknowledgedOperations" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>PrimaryWaitForPendingQuorumsTimeout -<see cref="P:System.Fabric.ReplicatorSettings.PrimaryWaitForPendingQuorumsTimeout" />値 (秒)</para>
              </description>
            </item>
            <item>
              <description>
                <para>UseStreamFaultsAndEndOfStreamOperationAck-<see cref="P:System.Fabric.ReplicatorSettings.UseStreamFaultsAndEndOfStreamOperationAck" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>InitialPrimaryReplicationQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.InitialPrimaryReplicationQueueSize" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>InitialSecondaryReplicationQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.InitialSecondaryReplicationQueueSize" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>MaxPrimaryReplicationQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueSize" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>MaxSecondaryReplicationQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueSize" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>MaxPrimaryReplicationQueueMemorySize-<see cref="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueMemorySize" /></para>
              </description>
            </item>
            <item>
              <description>
                <para>MaxSecondaryReplicationQueueMemorySize-<see cref="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueMemorySize" /></para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxCopyQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxCopyQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxCopyQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxCopyQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxCopyQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxCopyQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxCopyQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定、キューの最大サイズ、コピー操作の内部<see cref="T:System.Fabric.FabricReplicator" />、コピーが含まれています<see cref="T:System.Fabric.IOperation" />追加されていないと、サービスによって処理されます。</para>
        </summary>
        <value>
          <para>内のコピー操作キューの最大サイズ<see cref="T:System.Fabric.FabricReplicator" />、コピーが含まれています<see cref="T:System.Fabric.IOperation" />追加されていないと、サービスによって処理されます。</para>
        </value>
        <remarks>
          <para>このキューのサイズに達した場合、セカンダリで、プライマリのコピーのキューに操作がバッファーされます。 かどうかには、そのキューを格納、し、プライマリの表示が開始<see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" />例外。</para>
          <para>既定値は 1024</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPrimaryReplicationQueueMemorySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxPrimaryReplicationQueueMemorySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxPrimaryReplicationQueueMemorySize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPrimaryReplicationQueueMemorySize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxPrimaryReplicationQueueMemorySize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueMemorySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>内のプライマリ レプリケーション操作キューの最大サイズを定義<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />s</para>
        </summary>
        <value>
          <para>が必要です。 内のプライマリ レプリケーション操作キューの最大サイズを返します<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />単位をここでは、キューの仮想メモリの消費します。返します<see cref="T:System.Int64" />です。</para>
        </value>
        <remarks>
          <para>この設定は、サービスのロールがプライマリにレプリケーターに固有です。 既定値は 0 です。 つまり、メモリの制限はありません。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPrimaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxPrimaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxPrimaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPrimaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxPrimaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>内のプライマリ レプリケーション操作キューの最大サイズを定義<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />s</para>
        </summary>
        <value>
          <para>最大キューのサイズ、プライマリ レプリケーション操作の内部<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />s。 単位をここでは、キュー内の操作の数です。</para>
        </value>
        <remarks>
          <para>このキューのサイズに達したかどうかは、プライマリの表示が開始<see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" />例外。</para>
          <para>既定値は、このパラメーターの値は 1024 のメモが 2 の累乗にする必要があります。</para>
          <para>サービスのロールがプライマリである場合は、この設定は、複製物作成会社に固有</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReplicationMessageSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxReplicationMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxReplicationMessageSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxReplicationMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReplicationMessageSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxReplicationMessageSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxReplicationMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはレプリケーター経由で送信できるメッセージの最大サイズを設定します。 メッセージをコピーして、コンテキストのメッセージをコピーするこれらレプリケーション メッセージが含まれます。 表現の単位はバイトです。</para>
        </summary>
        <value>
          <para>レプリケーター経由で送信できるメッセージの最大サイズ。</para>
        </value>
        <remarks>
          <para>既定値は 50 MB です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReplicationQueueMemorySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxReplicationQueueMemorySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxReplicationQueueMemorySize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxReplicationQueueMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReplicationQueueMemorySize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxReplicationQueueMemorySize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxReplicationQueueMemorySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはレプリケーション キューのメモリの最大サイズを設定します。</para>
        </summary>
        <value>
          <para>レプリケーション キューのメモリの最大サイズ。</para>
        </value>
        <remarks>
          <para>既定値は 0 です。 つまり、メモリの制限はありません。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはレプリケーション キューの最大サイズを設定します。</para>
        </summary>
        <value>
          <para>レプリケーション キューの最大サイズ。</para>
        </value>
        <remarks>
          <para />
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSecondaryReplicationQueueMemorySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxSecondaryReplicationQueueMemorySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxSecondaryReplicationQueueMemorySize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSecondaryReplicationQueueMemorySize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxSecondaryReplicationQueueMemorySize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueMemorySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>内のセカンダリのレプリケーション操作キューの最大サイズを定義<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />s。</para>
        </summary>
        <value>
          <para>内のセカンダリのレプリケーション操作キューの最大サイズを返します<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />s。 単位をここでは、キューの仮想メモリの消費です。</para>
        </value>
        <remarks>
          <para>この設定は、サービスの役割がセカンダリ/アイドル状態の場合、レプリケーターに固有です。 既定値は 0 です。 つまり、メモリの制限はありません。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSecondaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxSecondaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxSecondaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSecondaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxSecondaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>内のセカンダリのレプリケーション操作キューの最大サイズを定義<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />s </para>
        </summary>
        <value>
          <para>内のセカンダリのレプリケーション操作キューの最大サイズ<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />追加されていないと、サービスによって処理されます。 単位をここでは、キューの操作の数</para>
        </value>
        <remarks>
          <para>このキューのサイズに達すると、プライマリのレプリケーション キューで操作がバッファーされます。  かどうかには、そのキューを格納、し、プライマリの表示が開始<see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" />例外。</para>
          <para>既定値は、このパラメーターの値が 2048.Note が 2 の累乗にする必要があります。</para>
          <para>サービスの役割がセカンダリ/アイドル状態の場合は、この設定は、複製物作成会社に固有</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryWaitForPendingQuorumsTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; PrimaryWaitForPendingQuorumsTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; PrimaryWaitForPendingQuorumsTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.PrimaryWaitForPendingQuorumsTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryWaitForPendingQuorumsTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.PrimaryWaitForPendingQuorumsTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.PrimaryWaitForPendingQuorumsTimeout" />
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
          <para>保留中のレプリケーション操作を取り消すにつながる可能性のある再構成要求を処理する前に、保留中のレプリケーション操作の確認のクォーラムを受信するため、主にレプリケーターが待機する時間を定義します。</para>
        </summary>
        <value>
          <para>プライマリのレプリケーターが再構成を処理するプライマリ レプリケーターの要求がある場合に、保留中のレプリケーション操作に対して受信確認のクォーラムを受信するために待機する時間<see cref="T:System.TimeSpan" />です。</para>
        </value>
        <remarks>
          <para>既定値は 0 です。 これは、保留中のレプリケーション操作でのクォーラムを受信するために再構成いない待機したことを意味します。 これは、再構成を早く完了するために役立ちます。 フェールオーバーをプライマリに長い期間の暗黙的な低速の再構成にこのパラメーターの値が大きいが生じる可能性があることに注意してください。 </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorAddress">
      <MemberSignature Language="C#" Value="public string ReplicatorAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.ReplicatorAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicatorAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorAddress : string with get, set" Usage="System.Fabric.ReplicatorSettings.ReplicatorAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>その他の複製物作成会社と通信するときにこの複製物作成会社が使用するアドレスを構成します。</para>
        </summary>
        <value>
          <para>その他の複製物作成会社と通信するときにこの複製物作成会社が使用するアドレス。</para>
        </value>
        <remarks>
          <para>書式設定された文字列として"hostname:port"ホスト名が FQDN または IP アドレスを指定できます。 既定値は、localhost:0 です。 レプリケーターがコンテナーの内部実行されている場合は、セットアップをやり直す必要があります<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorListenAddress" />と<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorListenAddress">
      <MemberSignature Language="C#" Value="public string ReplicatorListenAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorListenAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.ReplicatorListenAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicatorListenAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorListenAddress : string with get, set" Usage="System.Fabric.ReplicatorSettings.ReplicatorListenAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>この複製物作成会社が他の複製物作成会社から情報を受信に使用するリッスン アドレスを構成します。</para>
        </summary>
        <value>
          <para>この複製物作成会社が他の複製物作成会社から情報を受信に使用するリッスン アドレスです。</para>
        </value>
        <remarks>
          <para>書式設定された文字列として"hostname:port"ホスト名が FQDN または IP アドレスを指定できます。 既定値は、localhost:0 です。 リッスン アドレスのホスト名から取得できます。<see cref="P:System.Fabric.CodePackageActivationContext.ServiceListenAddress" /></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorPublishAddress">
      <MemberSignature Language="C#" Value="public string ReplicatorPublishAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorPublishAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicatorPublishAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorPublishAddress : string with get, set" Usage="System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>この複製物作成会社が他の複製物作成会社に情報を送信に使用する発行アドレスを構成します。</para>
        </summary>
        <value>
          <para>この複製物作成会社が他の複製物作成会社に情報を送信に使用する発行アドレスです。</para>
        </value>
        <remarks>
          <para>書式設定された文字列として"hostname:port"ホスト名が FQDN または IP アドレスを指定できます。 既定値は、localhost:0 です。 発行アドレスのホスト名を取得できます。<see cref="P:System.Fabric.CodePackageActivationContext.ServicePublishAddress" /></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequireServiceAck">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequireServiceAck { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequireServiceAck" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.RequireServiceAck" />
      <MemberSignature Language="VB.NET" Value="Public Property RequireServiceAck As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequireServiceAck : Nullable&lt;bool&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.RequireServiceAck" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>により、サービスを呼び出すオプティミスティックの受信確認要求することで非永続的なサービスの操作の<see cref="M:System.Fabric.IOperation.Acknowledge" />次の操作をポンプする前にします。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>場合、オプティミスティックの受信確認の非永続的なサービス操作のそれ以外の場合、 <languageKeyword>false</languageKeyword>です。</para>
        </value>
        <remarks>
          <para>明示的な受信確認を必要とする非永続的サービスは、レプリケーターによって操作のオプティミスティックの受信確認を防ぐために、True にこのプロパティを設定できます。 この設定は、永続的なサービスの影響を与えません。 </para>
          <para>既定値は false です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RetryInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RetryInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.RetryInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RetryInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.RetryInterval" />
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
          <para>定義しますが、どのくらいの期間<see cref="T:System.Fabric.FabricReplicator" />は、プライマリからのメッセージを受信したことを確認するセカンダリ セカンダリへのメッセージを送信後に待機します。</para>
        </summary>
        <value>
          <para>必要な時間、<see cref="T:System.Fabric.FabricReplicator" />は、プライマリからのメッセージを受信したことを確認するセカンダリ セカンダリへのメッセージを送信後に待機します。</para>
        </value>
        <remarks>
          <para>メッセージの受信が必ずしもメッセージが処理されたことです。</para>
          <para>このタイマーを超えた場合、メッセージが再送信されます。</para>
          <para>既定値は、5 秒です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryClearAcknowledgedOperations">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SecondaryClearAcknowledgedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SecondaryClearAcknowledgedOperations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.SecondaryClearAcknowledgedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryClearAcknowledgedOperations As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SecondaryClearAcknowledgedOperations : Nullable&lt;bool&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.SecondaryClearAcknowledgedOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>通常、セカンダリのレプリケーターに操作にできる catchup レプリカにプライマリに昇格の場合、キューに保持されます。 このフラグを有効にすると、セカンダリに複製物作成会社は、ユーザーのサービスによって承認されるとすぐに、操作を解放します。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>場合は、それ以外のユーザーのサービスによって受信確認を送ったとすぐに、セカンダリのレプリケーター解放操作<languageKeyword>false</languageKeyword>です。</para>
        </value>
        <remarks>
          <para>既定値は false</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityCredentials">
      <MemberSignature Language="C#" Value="public System.Fabric.SecurityCredentials SecurityCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SecurityCredentials SecurityCredentials" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.SecurityCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityCredentials As SecurityCredentials" />
      <MemberSignature Language="F#" Value="member this.SecurityCredentials : System.Fabric.SecurityCredentials with get, set" Usage="System.Fabric.ReplicatorSettings.SecurityCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SecurityCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>使用サービスが複製物作成会社間のトラフィックを保護するためのセキュリティ資格情報を定義できます。</para>
        </summary>
        <value>
          <para>複製物作成会社間のトラフィックを保護するためのセキュリティ資格情報を定義するサービス。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseStreamFaultsAndEndOfStreamOperationAck">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UseStreamFaultsAndEndOfStreamOperationAck { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UseStreamFaultsAndEndOfStreamOperationAck" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.UseStreamFaultsAndEndOfStreamOperationAck" />
      <MemberSignature Language="VB.NET" Value="Public Property UseStreamFaultsAndEndOfStreamOperationAck As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UseStreamFaultsAndEndOfStreamOperationAck : Nullable&lt;bool&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.UseStreamFaultsAndEndOfStreamOperationAck" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>