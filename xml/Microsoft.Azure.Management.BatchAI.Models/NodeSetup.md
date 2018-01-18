<Type Name="NodeSetup" FullName="Microsoft.Azure.Management.BatchAI.Models.NodeSetup">
  <TypeSignature Language="C#" Value="public class NodeSetup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeSetup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.NodeSetup" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeSetup" />
  <TypeSignature Language="F#" Value="type NodeSetup = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9ceb4-101">VM を準備するのにには、これを使用します。</span><span class="sxs-lookup"><span data-stu-id="9ceb4-101">Use this to prepare the VM.</span></span> <span data-ttu-id="9ceb4-102">メモ: mountVolumes で指定されたボリュームのマウントされた最初およびし、setupTask を実行します。</span><span class="sxs-lookup"><span data-stu-id="9ceb4-102">NOTE: The volumes specified in mountVolumes are mounted first and then the setupTask is run.</span></span> <span data-ttu-id="9ceb4-103">したがって、セットアップ タスクでは、その実行にローカル mountPaths を使用できます。</span><span class="sxs-lookup"><span data-stu-id="9ceb4-103">Therefore the setup task can use local mountPaths in its execution.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeSetup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.NodeSetup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9ceb4-104">NodeSetup クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9ceb4-104">Initializes a new instance of the NodeSetup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeSetup (Microsoft.Azure.Management.BatchAI.Models.SetupTask setupTask = null, Microsoft.Azure.Management.BatchAI.Models.MountVolumes mountVolumes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.BatchAI.Models.SetupTask setupTask, class Microsoft.Azure.Management.BatchAI.Models.MountVolumes mountVolumes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.NodeSetup.#ctor(Microsoft.Azure.Management.BatchAI.Models.SetupTask,Microsoft.Azure.Management.BatchAI.Models.MountVolumes)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.NodeSetup : Microsoft.Azure.Management.BatchAI.Models.SetupTask * Microsoft.Azure.Management.BatchAI.Models.MountVolumes -&gt; Microsoft.Azure.Management.BatchAI.Models.NodeSetup" Usage="new Microsoft.Azure.Management.BatchAI.Models.NodeSetup (setupTask, mountVolumes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="setupTask" Type="Microsoft.Azure.Management.BatchAI.Models.SetupTask" />
        <Parameter Name="mountVolumes" Type="Microsoft.Azure.Management.BatchAI.Models.MountVolumes" />
      </Parameters>
      <Docs>
        <param name="setupTask"><span data-ttu-id="9ceb4-105">クラスターのコンピューティング ノードをカスタマイズするために使用するセットアップ タスクを指定します。</span><span class="sxs-lookup"><span data-stu-id="9ceb4-105">Specifies a setup task which can be used to customize the compute nodes of the cluster.</span></span> <span data-ttu-id="9ceb4-106">NodeSetup タスクでは、VM が再起動されるたびに実行されます。</span><span class="sxs-lookup"><span data-stu-id="9ceb4-106">The NodeSetup task runs everytime a VM is rebooted.</span></span> <span data-ttu-id="9ceb4-107">そのため、タスクのコードはべき等である必要があります。</span><span class="sxs-lookup"><span data-stu-id="9ceb4-107">For that reason the task code needs to be idempotent.</span></span> <span data-ttu-id="9ceb4-108">通常、クラスター Vm 上で実行されるすべてのジョブに必要な静的データをダウンロードするか、または、ソフトウェアのダウンロードおよびインストールに使用されます。</span><span class="sxs-lookup"><span data-stu-id="9ceb4-108">Generally it is used to either download static data that is required for all jobs that run on the cluster VMs or to download/install software.</span></span></param>
        <param name="mountVolumes"><span data-ttu-id="9ceb4-109">ジョブによって使用される共有ボリュームについて説明します。</span><span class="sxs-lookup"><span data-stu-id="9ceb4-109">Information on shared volumes to be used by jobs.</span></span></param>
        <summary>
            <span data-ttu-id="9ceb4-110">NodeSetup クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9ceb4-110">Initializes a new instance of the NodeSetup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MountVolumes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.MountVolumes MountVolumes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.MountVolumes MountVolumes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.NodeSetup.MountVolumes" />
      <MemberSignature Language="VB.NET" Value="Public Property MountVolumes As MountVolumes" />
      <MemberSignature Language="F#" Value="member this.MountVolumes : Microsoft.Azure.Management.BatchAI.Models.MountVolumes with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.NodeSetup.MountVolumes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mountVolumes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.MountVolumes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9ceb4-111">取得またはジョブによって使用される共有ボリューム上の情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="9ceb4-111">Gets or sets information on shared volumes to be used by jobs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetupTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.SetupTask SetupTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.SetupTask SetupTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.NodeSetup.SetupTask" />
      <MemberSignature Language="VB.NET" Value="Public Property SetupTask As SetupTask" />
      <MemberSignature Language="F#" Value="member this.SetupTask : Microsoft.Azure.Management.BatchAI.Models.SetupTask with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.NodeSetup.SetupTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="setupTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.SetupTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9ceb4-112">取得または設定は、クラスターのコンピューティング ノードをカスタマイズするために使用するセットアップ タスクを指定します。</span><span class="sxs-lookup"><span data-stu-id="9ceb4-112">Gets or sets specifies a setup task which can be used to customize the compute nodes of the cluster.</span></span> <span data-ttu-id="9ceb4-113">NodeSetup タスクでは、VM が再起動されるたびに実行されます。</span><span class="sxs-lookup"><span data-stu-id="9ceb4-113">The NodeSetup task runs everytime a VM is rebooted.</span></span> <span data-ttu-id="9ceb4-114">そのため、タスクのコードはべき等である必要があります。</span><span class="sxs-lookup"><span data-stu-id="9ceb4-114">For that reason the task code needs to be idempotent.</span></span> <span data-ttu-id="9ceb4-115">通常、クラスター Vm 上で実行されるすべてのジョブに必要な静的データをダウンロードするか、または、ソフトウェアのダウンロードおよびインストールに使用されます。</span><span class="sxs-lookup"><span data-stu-id="9ceb4-115">Generally it is used to either download static data that is required for all jobs that run on the cluster VMs or to download/install software.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.NodeSetup.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="nodeSetup.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9ceb4-116">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="9ceb4-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9ceb4-117">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9ceb4-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>