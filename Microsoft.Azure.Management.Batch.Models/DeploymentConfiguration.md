<Type Name="DeploymentConfiguration" FullName="Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration">
  <TypeSignature Language="C#" Value="public class DeploymentConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeploymentConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class DeploymentConfiguration" />
  <TypeSignature Language="F#" Value="type DeploymentConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="af6e7-101">展開構成のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="af6e7-101">Deployment configuration properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="af6e7-102">DeploymentConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="af6e7-102">Initializes a new instance of the DeploymentConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentConfiguration (Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration cloudServiceConfiguration = null, Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration virtualMachineConfiguration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration cloudServiceConfiguration, class Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration virtualMachineConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration.#ctor(Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration,Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration : Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration * Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration -&gt; Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration" Usage="new Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration (cloudServiceConfiguration, virtualMachineConfiguration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="cloudServiceConfiguration" Type="Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration" />
        <Parameter Name="virtualMachineConfiguration" Type="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration" />
      </Parameters>
      <Docs>
        <param name="cloudServiceConfiguration"><span data-ttu-id="af6e7-103">プールのクラウドサービス構成。</span><span class="sxs-lookup"><span data-stu-id="af6e7-103">The cloud service configuration for the pool.</span></span></param>
        <param name="virtualMachineConfiguration"><span data-ttu-id="af6e7-104">プールの仮想マシン構成。</span><span class="sxs-lookup"><span data-stu-id="af6e7-104">The virtual machine configuration for the pool.</span></span></param>
        <summary>
            <span data-ttu-id="af6e7-105">DeploymentConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="af6e7-105">Initializes a new instance of the DeploymentConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudServiceConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration CloudServiceConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration CloudServiceConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration.CloudServiceConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudServiceConfiguration As CloudServiceConfiguration" />
      <MemberSignature Language="F#" Value="member this.CloudServiceConfiguration : Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration with get, set" Usage="Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration.CloudServiceConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cloudServiceConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="af6e7-106">取得またはプールをクラウド サービスの構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="af6e7-106">Gets or sets the cloud service configuration for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="af6e7-107">このプロパティと virtualMachineConfiguration は相互に排他的とプロパティのいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="af6e7-107">This property and virtualMachineConfiguration are mutually exclusive and one of the properties must be specified.</span></span> <span data-ttu-id="af6e7-108">このプロパティは、Batch アカウントが、poolAllocationMode プロパティ 'UserSubscription' に設定して作成されたかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="af6e7-108">This property cannot be specified if the Batch account was created with its poolAllocationMode property set to 'UserSubscription'.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="deploymentConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="af6e7-109">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="af6e7-109">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="af6e7-110">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af6e7-110">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration VirtualMachineConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration VirtualMachineConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration.VirtualMachineConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineConfiguration As VirtualMachineConfiguration" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineConfiguration : Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration with get, set" Usage="Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration.VirtualMachineConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualMachineConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="af6e7-111">取得またはプールの仮想マシンの構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="af6e7-111">Gets or sets the virtual machine configuration for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="af6e7-112">このプロパティと cloudServiceConfiguration は相互に排他的とプロパティのいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="af6e7-112">This property and cloudServiceConfiguration are mutually exclusive and one of the properties must be specified.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>