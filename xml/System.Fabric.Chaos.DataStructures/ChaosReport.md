<Type Name="ChaosReport" FullName="System.Fabric.Chaos.DataStructures.ChaosReport">
  <TypeSignature Language="C#" Value="public sealed class ChaosReport" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit ChaosReport extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Chaos.DataStructures.ChaosReport" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ChaosReport" />
  <TypeSignature Language="F#" Value="type ChaosReport = class" />
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
      <para><span data-ttu-id="f6289-101">によって返される可能性があります、時間の範囲内では混乱を実行中の状態を表す<see cref="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.Fabric.Chaos.DataStructures.ChaosReportFilter,System.TimeSpan,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="f6289-101">Represents the status of running Chaos, possibly within a time range, as returned by <see cref="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.Fabric.Chaos.DataStructures.ChaosReportFilter,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosReport (System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters, System.Fabric.Chaos.DataStructures.ChaosStatus status, System.Collections.Generic.List&lt;System.Fabric.Chaos.DataStructures.ChaosEvent&gt; history, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters, valuetype System.Fabric.Chaos.DataStructures.ChaosStatus status, class System.Collections.Generic.List`1&lt;class System.Fabric.Chaos.DataStructures.ChaosEvent&gt; history, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosReport.#ctor(System.Fabric.Chaos.DataStructures.ChaosParameters,System.Fabric.Chaos.DataStructures.ChaosStatus,System.Collections.Generic.List{System.Fabric.Chaos.DataStructures.ChaosEvent},System.String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.ChaosReport : System.Fabric.Chaos.DataStructures.ChaosParameters * System.Fabric.Chaos.DataStructures.ChaosStatus * System.Collections.Generic.List&lt;System.Fabric.Chaos.DataStructures.ChaosEvent&gt; * string -&gt; System.Fabric.Chaos.DataStructures.ChaosReport" Usage="new System.Fabric.Chaos.DataStructures.ChaosReport (chaosParameters, status, history, continuationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="chaosParameters" Type="System.Fabric.Chaos.DataStructures.ChaosParameters" />
        <Parameter Name="status" Type="System.Fabric.Chaos.DataStructures.ChaosStatus" />
        <Parameter Name="history" Type="System.Collections.Generic.List&lt;System.Fabric.Chaos.DataStructures.ChaosEvent&gt;" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="chaosParameters"><span data-ttu-id="f6289-102">Chaos が起動されているパラメーター</span><span class="sxs-lookup"><span data-stu-id="f6289-102">Parameters with which Chaos was started</span></span></param>
        <param name="status"><span data-ttu-id="f6289-103">場合の複雑さは、現在実行中か停止します。</span><span class="sxs-lookup"><span data-stu-id="f6289-103">If Chaos is currently running or stopped.</span></span></param>
        <param name="history"><span data-ttu-id="f6289-104">ChaosEvent の一覧の ChaosParameters で ChaosReportFilter と一致します。</span><span class="sxs-lookup"><span data-stu-id="f6289-104">The list of ChaosEvent's that match the ChaosReportFilter in ChaosParameters</span></span></param>
        <param name="continuationToken"><span data-ttu-id="f6289-105">イベントが多すぎる一致する場合、ChaosReportFilter、ものが複数のバッチに返されます、このトークンにより、バッチがリンクされています。</span><span class="sxs-lookup"><span data-stu-id="f6289-105">If too many events match the ChaosReportFilter, those will be returned in multiple batches, the batches are linked by this token.</span></span></param>
        <summary>
          <para><span data-ttu-id="f6289-106"><see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f6289-106">Initializes a new instance of the <see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChaosParameters">
      <MemberSignature Language="C#" Value="public System.Fabric.Chaos.DataStructures.ChaosParameters ChaosParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Chaos.DataStructures.ChaosParameters ChaosParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosReport.ChaosParameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ChaosParameters As ChaosParameters" />
      <MemberSignature Language="F#" Value="member this.ChaosParameters : System.Fabric.Chaos.DataStructures.ChaosParameters" Usage="System.Fabric.Chaos.DataStructures.ChaosReport.ChaosParameters" />
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
        <ReturnType>System.Fabric.Chaos.DataStructures.ChaosParameters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="f6289-107">渡されたパラメーターを取得<see cref="M:System.Fabric.FabricClient.TestManagementClient.StartChaosAsync(System.Fabric.Chaos.DataStructures.ChaosParameters,System.TimeSpan,System.Threading.CancellationToken)" />Chaos が起動されているとします。</span><span class="sxs-lookup"><span data-stu-id="f6289-107">Gets the parameters that was passed into <see cref="M:System.Fabric.FabricClient.TestManagementClient.StartChaosAsync(System.Fabric.Chaos.DataStructures.ChaosParameters,System.TimeSpan,System.Threading.CancellationToken)" /> and with which Chaos was started.</span></span></para>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosReport.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string" Usage="System.Fabric.Chaos.DataStructures.ChaosReport.ContinuationToken" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6289-108">Chaos イベントの数が大きすぎる場合、それらが返されますバッチです。そのため、ContinuationToken イベントの次のバッチを取得する必要があります、API 呼び出しで渡される<see cref="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="f6289-108">If the number of Chaos events is too large, then those will be returned in batches; so, to get the next batch of events the ContinuationToken must be passed in the API call, <see cref="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="History">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.List&lt;System.Fabric.Chaos.DataStructures.ChaosEvent&gt; History { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.List`1&lt;class System.Fabric.Chaos.DataStructures.ChaosEvent&gt; History" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosReport.History" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property History As List(Of ChaosEvent)" />
      <MemberSignature Language="F#" Value="member this.History : System.Collections.Generic.List&lt;System.Fabric.Chaos.DataStructures.ChaosEvent&gt;" Usage="System.Fabric.Chaos.DataStructures.ChaosReport.History" />
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
        <ReturnType>System.Collections.Generic.List&lt;System.Fabric.Chaos.DataStructures.ChaosEvent&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6289-109">指定された対象の期間中に生成された Chaos イベントの一覧を取得<see cref="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.Fabric.Chaos.DataStructures.ChaosReportFilter,System.TimeSpan,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="f6289-109">Gets the list of Chaos events that were produced during the time of interest specified in <see cref="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.Fabric.Chaos.DataStructures.ChaosReportFilter,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public System.Fabric.Chaos.DataStructures.ChaosStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Chaos.DataStructures.ChaosStatus Status" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosReport.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As ChaosStatus" />
      <MemberSignature Language="F#" Value="member this.Status : System.Fabric.Chaos.DataStructures.ChaosStatus" Usage="System.Fabric.Chaos.DataStructures.ChaosReport.Status" />
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
        <ReturnType>System.Fabric.Chaos.DataStructures.ChaosStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="f6289-110">現在のタスクを取得 (CurrentChaosTask で列挙子のいずれかの<c>enum</c>) Chaos を実行しています。</span><span class="sxs-lookup"><span data-stu-id="f6289-110">Gets the current task (one of the enumerators in CurrentChaosTask <c>enum</c>) that Chaos is performing.</span></span></para>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosReport.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="chaosReport.ToString " />
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
            <span data-ttu-id="f6289-111">Chaos の状態のオブジェクトの文字列表現を取得します。</span><span class="sxs-lookup"><span data-stu-id="f6289-111">Gets a string representation of the chaos status object.</span></span>
            </summary>
        <returns><span data-ttu-id="f6289-112">Chaos の状態のオブジェクトの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="f6289-112">A string representation of the chaos status object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>