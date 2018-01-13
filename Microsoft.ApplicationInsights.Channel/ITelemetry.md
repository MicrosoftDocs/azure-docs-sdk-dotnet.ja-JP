<Type Name="ITelemetry" FullName="Microsoft.ApplicationInsights.Channel.ITelemetry">
  <TypeSignature Language="C#" Value="public interface ITelemetry" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITelemetry" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Channel.ITelemetry" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITelemetry" />
  <TypeSignature Language="F#" Value="type ITelemetry = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6f578-101">Application insights の基本製品利用統計情報の種類。</span><span class="sxs-lookup"><span data-stu-id="6f578-101">The base telemetry type for application insights.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.ITelemetry.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As TelemetryContext" />
      <MemberSignature Language="F#" Value="member this.Context : Microsoft.ApplicationInsights.DataContracts.TelemetryContext" Usage="Microsoft.ApplicationInsights.Channel.ITelemetry.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.DataContracts.TelemetryContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6f578-102">この製品利用統計情報のインスタンスに関連付けられているコンテキストを取得します。</span><span class="sxs-lookup"><span data-stu-id="6f578-102">Gets the context associated with this telemetry instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeepClone">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Channel.ITelemetry.DeepClone" />
      <MemberSignature Language="VB.NET" Value="Public Function DeepClone () As ITelemetry" />
      <MemberSignature Language="F#" Value="abstract member DeepClone : unit -&gt; Microsoft.ApplicationInsights.Channel.ITelemetry" Usage="iTelemetry.DeepClone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Channel.ITelemetry</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sanitize">
      <MemberSignature Language="C#" Value="public void Sanitize ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Sanitize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize" />
      <MemberSignature Language="VB.NET" Value="Public Sub Sanitize ()" />
      <MemberSignature Language="F#" Value="abstract member Sanitize : unit -&gt; unit" Usage="iTelemetry.Sanitize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6f578-103">機能では、配布ポイントの制約に基づく製品利用統計情報項目のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="6f578-103">Sanitizes the properties of the telemetry item based on DP constraints.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sequence">
      <MemberSignature Language="C#" Value="public string Sequence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sequence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.ITelemetry.Sequence" />
      <MemberSignature Language="VB.NET" Value="Public Property Sequence As String" />
      <MemberSignature Language="F#" Value="member this.Sequence : string with get, set" Usage="Microsoft.ApplicationInsights.Channel.ITelemetry.Sequence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6f578-104">取得または製品利用統計情報アイテムの絶対順序を定義する値を設定します。</span><span class="sxs-lookup"><span data-stu-id="6f578-104">Gets or sets the value that defines absolute order of the telemetry item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6f578-105">シーケンスは、アップロードされるテレメトリのアイテムの絶対順序を追跡するために使用されます。</span><span class="sxs-lookup"><span data-stu-id="6f578-105">The sequence is used to track absolute order of uploaded telemetry items.</span></span> <span data-ttu-id="6f578-106">現在のブート セッションとアップロードのキューに追加された各イベントの識別子を増分するは安定した id を含む 2 部構成値である: これは 1 ずつ増分すべてのイベントのシステム全体の UTC です。</span><span class="sxs-lookup"><span data-stu-id="6f578-106">It is a two-part value that includes a stable identifier for the current boot session and an incrementing identifier for each event added to the upload queue: For UTC this would increment for all events across the system.</span></span>
            <span data-ttu-id="6f578-107">永続化のためには、ホストのプロセスから生成されたすべてのイベントのインクリメントこれはします。</span><span class="sxs-lookup"><span data-stu-id="6f578-107">For Persistence this would increment for all events emitted from the hosting process.</span></span>    
            <span data-ttu-id="6f578-108">シーケンスは、追跡イベントの数が起動され、イベントの数がアップロードされたされ、アップロードと受信サーバー上のイベントの重複除去の間に失われるデータの識別を有効にします。</span><span class="sxs-lookup"><span data-stu-id="6f578-108">The Sequence helps track how many events were fired and how many events were uploaded and enables identification of data lost during upload and de-duplication of events on the ingress server.</span></span>
            <span data-ttu-id="6f578-109"><a href="https://microsoft.sharepoint.com/teams/CommonSchema/Shared%20Documents/Schema%20Specs/Common%20Schema%202%20-%20Language%20Specification.docx" />です。</span><span class="sxs-lookup"><span data-stu-id="6f578-109">From <a href="https://microsoft.sharepoint.com/teams/CommonSchema/Shared%20Documents/Schema%20Specs/Common%20Schema%202%20-%20Language%20Specification.docx" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.ITelemetry.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.ApplicationInsights.Channel.ITelemetry.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6f578-110">取得または日付と時刻の製品利用統計情報が記録されるタイミングを設定します。</span><span class="sxs-lookup"><span data-stu-id="6f578-110">Gets or sets date and time when telemetry was recorded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>