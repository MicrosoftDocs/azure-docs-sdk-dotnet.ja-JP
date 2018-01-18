<Type Name="ComposeDeploymentStatusQueryDescription" FullName="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ComposeDeploymentStatusQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ComposeDeploymentStatusQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ComposeDeploymentStatusQueryDescription" />
  <TypeSignature Language="F#" Value="type ComposeDeploymentStatusQueryDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="4261a-101">System.Fabric.FabricClient.ComposeDeploymentClient.GetComposeDeploymentStatusPagedListAsync(Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription) で使用されるクエリの入力を表します。</span><span class="sxs-lookup"><span data-stu-id="4261a-101">Represents the query input used by System.Fabric.FabricClient.ComposeDeploymentClient.GetComposeDeploymentStatusPagedListAsync(Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription) .</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComposeDeploymentStatusQueryDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="4261a-102">インスタンスをインスタンス化<see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="4261a-102">Instantiates an instance of <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="4261a-103">取得または次のページを取得するクエリで使用できるトークンを設定します。</span><span class="sxs-lookup"><span data-stu-id="4261a-103">Gets or sets the token that can be used by queries to get the next page.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="4261a-104">次のページを取得するクエリで使用できるトークンです。</span><span class="sxs-lookup"><span data-stu-id="4261a-104">The token that can be used by queries to get the next page.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="4261a-105">ContinuationToken は、前のクエリによって受信されます。</span><span class="sxs-lookup"><span data-stu-id="4261a-105">ContinuationToken is received by a previous query.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentNameFilter">
      <MemberSignature Language="C#" Value="public string DeploymentNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeploymentNameFilter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.DeploymentNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property DeploymentNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.DeploymentNameFilter : string with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.DeploymentNameFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="4261a-106">取得または設定の名前は、クエリを実行する展開を作成します。</span><span class="sxs-lookup"><span data-stu-id="4261a-106">Gets or sets the name of compose deployment to query for.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="4261a-107">名前は、クエリを実行する展開を作成します。</span><span class="sxs-lookup"><span data-stu-id="4261a-107">The name of compose deployment to query for.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="4261a-108">展開を作成すべて DeploymentNameFilter が指定されていない場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4261a-108">If DeploymentNameFilter is not specified, all compose deployments are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public long MaxResults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxResults As Long" />
      <MemberSignature Language="F#" Value="member this.MaxResults : int64 with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.MaxResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4261a-109">取得またはページごとに返されることができます Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItems の最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="4261a-109">Gets or sets the max number of Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItems that can be returned per page.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="4261a-110">この値が設定されていない場合、返された Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItems の数を制限するのには使用されません。</span><span class="sxs-lookup"><span data-stu-id="4261a-110">If this value is not set, it is not used to limit the number of returned Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItems.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>