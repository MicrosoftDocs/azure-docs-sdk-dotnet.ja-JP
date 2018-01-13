<Type Name="IReplicationLink" FullName="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink">
  <TypeSignature Language="C#" Value="public interface IReplicationLink : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Sql.Fluent.IReplicationLink&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReplicationLink implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.IReplicationLink&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReplicationLink&#xA;Implements IHasId, IHasInner(Of ReplicationLinkInner), IHasName, IHasResourceGroup, IRefreshable(Of IReplicationLink)" />
  <TypeSignature Language="F#" Value="type IReplicationLink = interface&#xA;    interface IRefreshable&lt;IReplicationLink&gt;&#xA;    interface IHasInner&lt;ReplicationLinkInner&gt;&#xA;    interface IHasResourceGroup&#xA;    interface IHasName&#xA;    interface IHasId" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Sql.Fluent.IReplicationLink&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="bf7de-101">Azure SQL レプリケーション リンクの変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="bf7de-101">An immutable client-side representation of an Azure SQL Replication link.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.DatabaseName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf7de-102">このレプリケーションが所属する SQL データベースの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf7de-102">Gets name of the SQL Database to which this replication belongs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.Delete" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete ()" />
      <MemberSignature Language="F#" Value="abstract member Delete : unit -&gt; unit" Usage="iReplicationLink.Delete " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bf7de-103">レプリケーション リンクを削除します。</span><span class="sxs-lookup"><span data-stu-id="bf7de-103">Deletes the replication link.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Failover">
      <MemberSignature Language="C#" Value="public void Failover ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Failover() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.Failover" />
      <MemberSignature Language="VB.NET" Value="Public Sub Failover ()" />
      <MemberSignature Language="F#" Value="abstract member Failover : unit -&gt; unit" Usage="iReplicationLink.Failover " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bf7de-104">Azure SQL データベース レプリケーション リンクでは失敗します。</span><span class="sxs-lookup"><span data-stu-id="bf7de-104">Fails over the Azure SQL Database Replication Link.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task FailoverAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FailoverAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.FailoverAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member FailoverAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReplicationLink.FailoverAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="bf7de-105">Azure SQL データベース レプリケーション リンクでは失敗します。</span><span class="sxs-lookup"><span data-stu-id="bf7de-105">Fails over the Azure SQL Database Replication Link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf7de-106">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="bf7de-106">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="bf7de-107">この呼び出しの遅延の計算の表現。</span><span class="sxs-lookup"><span data-stu-id="bf7de-107">A representation of the deferred computation of this call.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ForceFailoverAllowDataLoss">
      <MemberSignature Language="C#" Value="public void ForceFailoverAllowDataLoss ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ForceFailoverAllowDataLoss() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.ForceFailoverAllowDataLoss" />
      <MemberSignature Language="VB.NET" Value="Public Sub ForceFailoverAllowDataLoss ()" />
      <MemberSignature Language="F#" Value="abstract member ForceFailoverAllowDataLoss : unit -&gt; unit" Usage="iReplicationLink.ForceFailoverAllowDataLoss " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bf7de-108">強制的にフェールオーバー、Azure SQL データベース レプリケーション リンク データの損失になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="bf7de-108">Forces fail over the Azure SQL Database Replication Link which may result in data loss.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceFailoverAllowDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ForceFailoverAllowDataLossAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ForceFailoverAllowDataLossAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.ForceFailoverAllowDataLossAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ForceFailoverAllowDataLossAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReplicationLink.ForceFailoverAllowDataLossAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="bf7de-109">強制的にフェールオーバー、Azure SQL データベース レプリケーション リンク データの損失になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="bf7de-109">Forces fail over the Azure SQL Database Replication Link which may result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bf7de-110">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="bf7de-110">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="bf7de-111">この呼び出しの遅延の計算の表現。</span><span class="sxs-lookup"><span data-stu-id="bf7de-111">A representation of the deferred computation of this call.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="PartnerDatabase">
      <MemberSignature Language="C#" Value="public string PartnerDatabase { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartnerDatabase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PartnerDatabase" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerDatabase As String" />
      <MemberSignature Language="F#" Value="member this.PartnerDatabase : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PartnerDatabase" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf7de-112">Azure SQL データベースのパートナーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf7de-112">Gets the name of the partner Azure SQL Database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerLocation">
      <MemberSignature Language="C#" Value="public string PartnerLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartnerLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PartnerLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerLocation As String" />
      <MemberSignature Language="F#" Value="member this.PartnerLocation : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PartnerLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf7de-113">Azure SQL データベースのパートナーの Azure リージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="bf7de-113">Gets the Azure Region of the partner Azure SQL Database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerRole">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole PartnerRole { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole PartnerRole" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PartnerRole" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerRole As ReplicationRole" />
      <MemberSignature Language="F#" Value="member this.PartnerRole : Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PartnerRole" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf7de-114">レプリケーション リンクでは、パートナー SQL データベースの役割を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf7de-114">Gets the role of the partner SQL Database in the replication link.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerServer">
      <MemberSignature Language="C#" Value="public string PartnerServer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartnerServer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PartnerServer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerServer As String" />
      <MemberSignature Language="F#" Value="member this.PartnerServer : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PartnerServer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf7de-115">Azure SQL データベースのパートナーをホストする Azure の SQL Server の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf7de-115">Gets the name of the Azure SQL Server hosting the partner Azure SQL Database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentComplete">
      <MemberSignature Language="C#" Value="public int PercentComplete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PercentComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PercentComplete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PercentComplete As Integer" />
      <MemberSignature Language="F#" Value="member this.PercentComplete : int" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PercentComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf7de-116">レプリケーション リンクの完了のシード処理の割合を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf7de-116">Gets the percentage of the seeding completed for the replication link.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicationState">
      <MemberSignature Language="C#" Value="public string ReplicationState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicationState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.ReplicationState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicationState As String" />
      <MemberSignature Language="F#" Value="member this.ReplicationState : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.ReplicationState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf7de-117">レプリケーション リンクのレプリケーション状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf7de-117">Gets the replication state for the replication link.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Role">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole Role { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole Role" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.Role" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Role As ReplicationRole" />
      <MemberSignature Language="F#" Value="member this.Role : Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.Role" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf7de-118">レプリケーション リンクには、SQL データベースの役割を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf7de-118">Gets the role of the SQL Database in the replication link.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerName">
      <MemberSignature Language="C#" Value="public string SqlServerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlServerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.SqlServerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SqlServerName As String" />
      <MemberSignature Language="F#" Value="member this.SqlServerName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.SqlServerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf7de-119">このレプリケーションが所属する SQL Server の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf7de-119">Gets name of the SQL Server to which this replication belongs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf7de-120">取得の開始時刻、レプリケーション リンク (ISO8601 形式)。</span><span class="sxs-lookup"><span data-stu-id="bf7de-120">Gets start time for the replication link (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>