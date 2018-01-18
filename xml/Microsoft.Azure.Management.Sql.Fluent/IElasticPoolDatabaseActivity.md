<Type Name="IElasticPoolDatabaseActivity" FullName="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity">
  <TypeSignature Language="C#" Value="public interface IElasticPoolDatabaseActivity : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolDatabaseActivityInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IElasticPoolDatabaseActivity implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolDatabaseActivityInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity" />
  <TypeSignature Language="VB.NET" Value="Public Interface IElasticPoolDatabaseActivity&#xA;Implements IHasId, IHasInner(Of ElasticPoolDatabaseActivityInner), IHasName, IHasResourceGroup" />
  <TypeSignature Language="F#" Value="type IElasticPoolDatabaseActivity = interface&#xA;    interface IHasInner&lt;ElasticPoolDatabaseActivityInner&gt;&#xA;    interface IHasResourceGroup&#xA;    interface IHasName&#xA;    interface IHasId" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolDatabaseActivityInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="6429e-101">Azure SQL ElasticPool のデータベースの利用状況の変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="6429e-101">An immutable client-side representation of an Azure SQL ElasticPool's Database Activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CurrentElasticPoolName">
      <MemberSignature Language="C#" Value="public string CurrentElasticPoolName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentElasticPoolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.CurrentElasticPoolName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentElasticPoolName As String" />
      <MemberSignature Language="F#" Value="member this.CurrentElasticPoolName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.CurrentElasticPoolName" />
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
            <span data-ttu-id="6429e-102">場合に、データベースは、現在のエラスティック プールの名前を取得使用できます。</span><span class="sxs-lookup"><span data-stu-id="6429e-102">Gets the name of the current Elastic Pool the database is in if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentServiceObjective">
      <MemberSignature Language="C#" Value="public string CurrentServiceObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentServiceObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.CurrentServiceObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentServiceObjective As String" />
      <MemberSignature Language="F#" Value="member this.CurrentServiceObjective : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.CurrentServiceObjective" />
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
            <span data-ttu-id="6429e-103">使用可能な場合は、現在のサービス目標の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="6429e-103">Gets the name of the current service objective if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.DatabaseName" />
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
            <span data-ttu-id="6429e-104">データベース名を取得します。</span><span class="sxs-lookup"><span data-stu-id="6429e-104">Gets the database name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public DateTime EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.EndTime : DateTime" Usage="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.EndTime" />
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
            <span data-ttu-id="6429e-105">操作 (ISO8601 形式) が終了した時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="6429e-105">Gets the time the operation finished (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public int ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As Integer" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : int" Usage="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.ErrorCode" />
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
            <span data-ttu-id="6429e-106">使用可能な場合は、エラー コードを取得します。</span><span class="sxs-lookup"><span data-stu-id="6429e-106">Gets the error code if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public string ErrorMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.ErrorMessage" />
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
            <span data-ttu-id="6429e-107">使用可能な場合は、エラー メッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="6429e-107">Gets the error message if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorSeverity">
      <MemberSignature Language="C#" Value="public int ErrorSeverity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ErrorSeverity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.ErrorSeverity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorSeverity As Integer" />
      <MemberSignature Language="F#" Value="member this.ErrorSeverity : int" Usage="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.ErrorSeverity" />
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
            <span data-ttu-id="6429e-108">使用可能な場合は、エラーの重大度を取得します。</span><span class="sxs-lookup"><span data-stu-id="6429e-108">Gets the error severity if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public string Operation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.Operation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operation As String" />
      <MemberSignature Language="F#" Value="member this.Operation : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.Operation" />
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
            <span data-ttu-id="6429e-109">操作の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="6429e-109">Gets the operation name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationId">
      <MemberSignature Language="C#" Value="public string OperationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.OperationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationId As String" />
      <MemberSignature Language="F#" Value="member this.OperationId : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.OperationId" />
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
            <span data-ttu-id="6429e-110">一意の操作 ID を取得します</span><span class="sxs-lookup"><span data-stu-id="6429e-110">Gets the unique operation ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentComplete">
      <MemberSignature Language="C#" Value="public int PercentComplete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PercentComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.PercentComplete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PercentComplete As Integer" />
      <MemberSignature Language="F#" Value="member this.PercentComplete : int" Usage="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.PercentComplete" />
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
            <span data-ttu-id="6429e-111">パーセンテージを取得、完全な使用可能な場合です。</span><span class="sxs-lookup"><span data-stu-id="6429e-111">Gets the percentage complete if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedElasticPoolName">
      <MemberSignature Language="C#" Value="public string RequestedElasticPoolName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestedElasticPoolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.RequestedElasticPoolName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedElasticPoolName As String" />
      <MemberSignature Language="F#" Value="member this.RequestedElasticPoolName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.RequestedElasticPoolName" />
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
            <span data-ttu-id="6429e-112">データベースは、使用可能な場合に移行弾力性プールの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="6429e-112">Gets the name for the Elastic Pool the database is moving into if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedServiceObjective">
      <MemberSignature Language="C#" Value="public string RequestedServiceObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestedServiceObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.RequestedServiceObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedServiceObjective As String" />
      <MemberSignature Language="F#" Value="member this.RequestedServiceObjective : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.RequestedServiceObjective" />
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
            <span data-ttu-id="6429e-113">使用可能な場合は、要求されたサービス目標の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="6429e-113">Gets the name of the requested service objective if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerName">
      <MemberSignature Language="C#" Value="public string ServerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.ServerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerName As String" />
      <MemberSignature Language="F#" Value="member this.ServerName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.ServerName" />
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
            <span data-ttu-id="6429e-114">弾力性プールが、Azure の SQL Server の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="6429e-114">Gets the name of the Azure SQL Server the Elastic Pool is in.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.StartTime" />
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
            <span data-ttu-id="6429e-115">操作 (ISO8601 形式) が開始された時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="6429e-115">Gets the time the operation started (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolDatabaseActivity.State" />
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
            <span data-ttu-id="6429e-116">操作の現在の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="6429e-116">Gets the current state of the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>