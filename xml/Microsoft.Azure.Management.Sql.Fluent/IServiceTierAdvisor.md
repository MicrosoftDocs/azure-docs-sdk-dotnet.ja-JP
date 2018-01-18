<Type Name="IServiceTierAdvisor" FullName="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor">
  <TypeSignature Language="C#" Value="public interface IServiceTierAdvisor : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceTierAdvisor implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceTierAdvisor&#xA;Implements IHasId, IHasInner(Of ServiceTierAdvisorInner), IHasName, IHasResourceGroup, IRefreshable(Of IServiceTierAdvisor)" />
  <TypeSignature Language="F#" Value="type IServiceTierAdvisor = interface&#xA;    interface IRefreshable&lt;IServiceTierAdvisor&gt;&#xA;    interface IHasInner&lt;ServiceTierAdvisorInner&gt;&#xA;    interface IHasResourceGroup&#xA;    interface IHasName&#xA;    interface IHasId" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="ba5b8-101">Azure SQL のサービス層アドバイザーの変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-101">An immutable client-side representation of an Azure SQL Service tier advisor.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ActiveTimeRatio">
      <MemberSignature Language="C#" Value="public double ActiveTimeRatio { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 ActiveTimeRatio" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.ActiveTimeRatio" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActiveTimeRatio As Double" />
      <MemberSignature Language="F#" Value="member this.ActiveTimeRatio : double" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.ActiveTimeRatio" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba5b8-102">サービス層アドバイザー activeTimeRatio を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-102">Gets the activeTimeRatio for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvgDtu">
      <MemberSignature Language="C#" Value="public double AvgDtu { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 AvgDtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.AvgDtu" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvgDtu As Double" />
      <MemberSignature Language="F#" Value="member this.AvgDtu : double" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.AvgDtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba5b8-103">取得またはサービス層アドバイザー avgDtu を設定します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-103">Gets or sets avgDtu for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Confidence">
      <MemberSignature Language="C#" Value="public double Confidence { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Confidence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.Confidence" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Confidence As Double" />
      <MemberSignature Language="F#" Value="member this.Confidence : double" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.Confidence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba5b8-104">取得またはサービス層アドバイザーの信頼度を設定します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-104">Gets or sets confidence for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string CurrentServiceLevelObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.CurrentServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.CurrentServiceLevelObjective : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.CurrentServiceLevelObjective" />
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
            <span data-ttu-id="ba5b8-105">取得またはサービス層アドバイザー currentServiceLevelObjective を設定します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-105">Gets or sets currentServiceLevelObjective for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentServiceLevelObjectiveId">
      <MemberSignature Language="C#" Value="public Guid CurrentServiceLevelObjectiveId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid CurrentServiceLevelObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.CurrentServiceLevelObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentServiceLevelObjectiveId As Guid" />
      <MemberSignature Language="F#" Value="member this.CurrentServiceLevelObjectiveId : Guid" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.CurrentServiceLevelObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba5b8-106">取得またはサービス層アドバイザー currentServiceLevelObjectiveId を設定します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-106">Gets or sets currentServiceLevelObjectiveId for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.DatabaseName" />
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
            <span data-ttu-id="ba5b8-107">このレプリケーションが所属する SQL データベースの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-107">Gets name of the SQL Database to which this replication belongs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseSizeBasedRecommendationServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string DatabaseSizeBasedRecommendationServiceLevelObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseSizeBasedRecommendationServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.DatabaseSizeBasedRecommendationServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseSizeBasedRecommendationServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseSizeBasedRecommendationServiceLevelObjective : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.DatabaseSizeBasedRecommendationServiceLevelObjective" />
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
            <span data-ttu-id="ba5b8-108">取得またはサービス層アドバイザー databaseSizeBasedRecommendationServiceLevelObjective を設定します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-108">Gets or sets databaseSizeBasedRecommendationServiceLevelObjective for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseSizeBasedRecommendationServiceLevelObjectiveId">
      <MemberSignature Language="C#" Value="public Guid DatabaseSizeBasedRecommendationServiceLevelObjectiveId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid DatabaseSizeBasedRecommendationServiceLevelObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.DatabaseSizeBasedRecommendationServiceLevelObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseSizeBasedRecommendationServiceLevelObjectiveId As Guid" />
      <MemberSignature Language="F#" Value="member this.DatabaseSizeBasedRecommendationServiceLevelObjectiveId : Guid" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.DatabaseSizeBasedRecommendationServiceLevelObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba5b8-109">取得またはサービス層アドバイザー databaseSizeBasedRecommendationServiceLevelObjectiveId を設定します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-109">Gets or sets databaseSizeBasedRecommendationServiceLevelObjectiveId for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisasterPlanBasedRecommendationServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string DisasterPlanBasedRecommendationServiceLevelObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisasterPlanBasedRecommendationServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.DisasterPlanBasedRecommendationServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisasterPlanBasedRecommendationServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.DisasterPlanBasedRecommendationServiceLevelObjective : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.DisasterPlanBasedRecommendationServiceLevelObjective" />
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
            <span data-ttu-id="ba5b8-110">取得またはサービス層アドバイザー disasterPlanBasedRecommendationServiceLevelObjective を設定します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-110">Gets or sets disasterPlanBasedRecommendationServiceLevelObjective for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisasterPlanBasedRecommendationServiceLevelObjectiveId">
      <MemberSignature Language="C#" Value="public Guid DisasterPlanBasedRecommendationServiceLevelObjectiveId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid DisasterPlanBasedRecommendationServiceLevelObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.DisasterPlanBasedRecommendationServiceLevelObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisasterPlanBasedRecommendationServiceLevelObjectiveId As Guid" />
      <MemberSignature Language="F#" Value="member this.DisasterPlanBasedRecommendationServiceLevelObjectiveId : Guid" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.DisasterPlanBasedRecommendationServiceLevelObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba5b8-111">取得またはサービス層アドバイザー disasterPlanBasedRecommendationServiceLevelObjectiveId を設定します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-111">Gets or sets disasterPlanBasedRecommendationServiceLevelObjectiveId for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDtu">
      <MemberSignature Language="C#" Value="public double MaxDtu { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 MaxDtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.MaxDtu" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxDtu As Double" />
      <MemberSignature Language="F#" Value="member this.MaxDtu : double" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.MaxDtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba5b8-112">取得またはサービス層アドバイザー maxDtu を設定します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-112">Gets or sets maxDtu for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeInGB">
      <MemberSignature Language="C#" Value="public double MaxSizeInGB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 MaxSizeInGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.MaxSizeInGB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxSizeInGB As Double" />
      <MemberSignature Language="F#" Value="member this.MaxSizeInGB : double" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.MaxSizeInGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba5b8-113">取得またはサービス層アドバイザー maxSizeInGB を設定します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-113">Gets or sets maxSizeInGB for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinDtu">
      <MemberSignature Language="C#" Value="public double MinDtu { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 MinDtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.MinDtu" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinDtu As Double" />
      <MemberSignature Language="F#" Value="member this.MinDtu : double" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.MinDtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba5b8-114">取得またはサービス層アドバイザー minDtu を設定します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-114">Gets or sets minDtu for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObservationPeriodEnd">
      <MemberSignature Language="C#" Value="public DateTime ObservationPeriodEnd { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ObservationPeriodEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.ObservationPeriodEnd" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ObservationPeriodEnd As DateTime" />
      <MemberSignature Language="F#" Value="member this.ObservationPeriodEnd : DateTime" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.ObservationPeriodEnd" />
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
            <span data-ttu-id="ba5b8-115">監視期間の開始 (ISO8601 形式) を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-115">Gets the observation period start (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObservationPeriodStart">
      <MemberSignature Language="C#" Value="public DateTime ObservationPeriodStart { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ObservationPeriodStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.ObservationPeriodStart" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ObservationPeriodStart As DateTime" />
      <MemberSignature Language="F#" Value="member this.ObservationPeriodStart : DateTime" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.ObservationPeriodStart" />
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
            <span data-ttu-id="ba5b8-116">監視期間の開始 (ISO8601 形式) を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-116">Gets the observation period start (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OverallRecommendationServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string OverallRecommendationServiceLevelObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OverallRecommendationServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.OverallRecommendationServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OverallRecommendationServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.OverallRecommendationServiceLevelObjective : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.OverallRecommendationServiceLevelObjective" />
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
            <span data-ttu-id="ba5b8-117">取得またはサービス層アドバイザー overallRecommendationServiceLevelObjective を設定します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-117">Gets or sets overallRecommendationServiceLevelObjective for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OverallRecommendationServiceLevelObjectiveId">
      <MemberSignature Language="C#" Value="public Guid OverallRecommendationServiceLevelObjectiveId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid OverallRecommendationServiceLevelObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.OverallRecommendationServiceLevelObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OverallRecommendationServiceLevelObjectiveId As Guid" />
      <MemberSignature Language="F#" Value="member this.OverallRecommendationServiceLevelObjectiveId : Guid" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.OverallRecommendationServiceLevelObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba5b8-118">取得またはサービス層アドバイザー overallRecommendationServiceLevelObjectiveId を設定します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-118">Gets or sets overallRecommendationServiceLevelObjectiveId for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceLevelObjectiveUsageMetrics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISloUsageMetricInterface&gt; ServiceLevelObjectiveUsageMetrics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISloUsageMetricInterface&gt; ServiceLevelObjectiveUsageMetrics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.ServiceLevelObjectiveUsageMetrics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceLevelObjectiveUsageMetrics As IReadOnlyList(Of ISloUsageMetricInterface)" />
      <MemberSignature Language="F#" Value="member this.ServiceLevelObjectiveUsageMetrics : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISloUsageMetricInterface&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.ServiceLevelObjectiveUsageMetrics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISloUsageMetricInterface&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba5b8-119">サービス層アドバイザーの serviceLevelObjectiveUsageMetrics を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-119">Gets serviceLevelObjectiveUsageMetrics for the service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerName">
      <MemberSignature Language="C#" Value="public string SqlServerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlServerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.SqlServerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SqlServerName As String" />
      <MemberSignature Language="F#" Value="member this.SqlServerName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.SqlServerName" />
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
            <span data-ttu-id="ba5b8-120">このレプリケーションが所属する SQL Server の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-120">Gets name of the SQL Server to which this replication belongs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageBasedRecommendationServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string UsageBasedRecommendationServiceLevelObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UsageBasedRecommendationServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.UsageBasedRecommendationServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsageBasedRecommendationServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.UsageBasedRecommendationServiceLevelObjective : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.UsageBasedRecommendationServiceLevelObjective" />
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
            <span data-ttu-id="ba5b8-121">取得またはサービス層アドバイザー usageBasedRecommendationServiceLevelObjective を設定します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-121">Gets or sets usageBasedRecommendationServiceLevelObjective for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageBasedRecommendationServiceLevelObjectiveId">
      <MemberSignature Language="C#" Value="public Guid UsageBasedRecommendationServiceLevelObjectiveId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid UsageBasedRecommendationServiceLevelObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.UsageBasedRecommendationServiceLevelObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsageBasedRecommendationServiceLevelObjectiveId As Guid" />
      <MemberSignature Language="F#" Value="member this.UsageBasedRecommendationServiceLevelObjectiveId : Guid" Usage="Microsoft.Azure.Management.Sql.Fluent.IServiceTierAdvisor.UsageBasedRecommendationServiceLevelObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba5b8-122">取得またはサービス層アドバイザー usageBasedRecommendationServiceLevelObjectiveId を設定します。</span><span class="sxs-lookup"><span data-stu-id="ba5b8-122">Gets or sets usageBasedRecommendationServiceLevelObjectiveId for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>