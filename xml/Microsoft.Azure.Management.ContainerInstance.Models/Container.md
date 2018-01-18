<Type Name="Container" FullName="Microsoft.Azure.Management.ContainerInstance.Models.Container">
  <TypeSignature Language="C#" Value="public class Container" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Container extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.Models.Container" />
  <TypeSignature Language="VB.NET" Value="Public Class Container" />
  <TypeSignature Language="F#" Value="type Container = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="7974d-101">コンテナーのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="7974d-101">A container instance.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Container ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.Container.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7974d-102">コンテナー クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7974d-102">Initializes a new instance of the Container class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Container (string name, string image, Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements resources, System.Collections.Generic.IList&lt;string&gt; command = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort&gt; ports = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.EnvironmentVariable&gt; environmentVariables = null, Microsoft.Azure.Management.ContainerInstance.Models.ContainerPropertiesInstanceView instanceView = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount&gt; volumeMounts = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string image, class Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements resources, class System.Collections.Generic.IList`1&lt;string&gt; command, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort&gt; ports, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.EnvironmentVariable&gt; environmentVariables, class Microsoft.Azure.Management.ContainerInstance.Models.ContainerPropertiesInstanceView instanceView, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount&gt; volumeMounts) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.Container.#ctor(System.String,System.String,Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort},System.Collections.Generic.IList{Microsoft.Azure.Management.ContainerInstance.Models.EnvironmentVariable},Microsoft.Azure.Management.ContainerInstance.Models.ContainerPropertiesInstanceView,System.Collections.Generic.IList{Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, image As String, resources As ResourceRequirements, Optional command As IList(Of String) = null, Optional ports As IList(Of ContainerPort) = null, Optional environmentVariables As IList(Of EnvironmentVariable) = null, Optional instanceView As ContainerPropertiesInstanceView = null, Optional volumeMounts As IList(Of VolumeMount) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerInstance.Models.Container : string * string * Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.EnvironmentVariable&gt; * Microsoft.Azure.Management.ContainerInstance.Models.ContainerPropertiesInstanceView * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount&gt; -&gt; Microsoft.Azure.Management.ContainerInstance.Models.Container" Usage="new Microsoft.Azure.Management.ContainerInstance.Models.Container (name, image, resources, command, ports, environmentVariables, instanceView, volumeMounts)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="image" Type="System.String" />
        <Parameter Name="resources" Type="Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements" />
        <Parameter Name="command" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="ports" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort&gt;" />
        <Parameter Name="environmentVariables" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.EnvironmentVariable&gt;" />
        <Parameter Name="instanceView" Type="Microsoft.Azure.Management.ContainerInstance.Models.ContainerPropertiesInstanceView" />
        <Parameter Name="volumeMounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7974d-103">コンテナーのインスタンスのユーザーが指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="7974d-103">The user-provided name of the container instance.</span></span></param>
        <param name="image"><span data-ttu-id="7974d-104">コンテナー インスタンスを作成するために使用するイメージの名前。</span><span class="sxs-lookup"><span data-stu-id="7974d-104">The name of the image used to create the container instance.</span></span></param>
        <param name="resources"><span data-ttu-id="7974d-105">コンテナーのインスタンスのリソース要件。</span><span class="sxs-lookup"><span data-stu-id="7974d-105">The resource requirements of the container instance.</span></span></param>
        <param name="command"><span data-ttu-id="7974d-106">Exec フォームのコンテナー インスタンス内で実行するコマンド。</span><span class="sxs-lookup"><span data-stu-id="7974d-106">The commands to execute within the container instance in exec form.</span></span></param>
        <param name="ports"><span data-ttu-id="7974d-107">コンテナーのインスタンスで公開されているポート。</span><span class="sxs-lookup"><span data-stu-id="7974d-107">The exposed ports on the container instance.</span></span></param>
        <param name="environmentVariables"><span data-ttu-id="7974d-108">コンテナーのインスタンスで設定する環境変数。</span><span class="sxs-lookup"><span data-stu-id="7974d-108">The environment variables to set in the container instance.</span></span></param>
        <param name="instanceView"><span data-ttu-id="7974d-109">コンテナーのインスタンスのインスタンス ビューです。</span><span class="sxs-lookup"><span data-stu-id="7974d-109">The instance view of the container instance.</span></span> <span data-ttu-id="7974d-110">応答でのみ有効です。</span><span class="sxs-lookup"><span data-stu-id="7974d-110">Only valid in response.</span></span></param>
        <param name="volumeMounts"><span data-ttu-id="7974d-111">ボリュームをマウント コンテナー インスタンスで使用します。</span><span class="sxs-lookup"><span data-stu-id="7974d-111">The volume mounts available to the container instance.</span></span></param>
        <summary>
            <span data-ttu-id="7974d-112">コンテナー クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7974d-112">Initializes a new instance of the Container class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Command">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Command { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Command" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.Container.Command" />
      <MemberSignature Language="VB.NET" Value="Public Property Command As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Command : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.Container.Command" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.command")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7974d-113">取得または exec フォームのコンテナー インスタンス内で実行するコマンドを設定します。</span><span class="sxs-lookup"><span data-stu-id="7974d-113">Gets or sets the commands to execute within the container instance in exec form.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentVariables">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.EnvironmentVariable&gt; EnvironmentVariables { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.EnvironmentVariable&gt; EnvironmentVariables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.Container.EnvironmentVariables" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentVariables As IList(Of EnvironmentVariable)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentVariables : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.EnvironmentVariable&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.Container.EnvironmentVariables" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.environmentVariables")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.EnvironmentVariable&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7974d-114">取得またはコンテナー インスタンスで設定する環境変数を設定します。</span><span class="sxs-lookup"><span data-stu-id="7974d-114">Gets or sets the environment variables to set in the container instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Image">
      <MemberSignature Language="C#" Value="public string Image { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Image" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.Container.Image" />
      <MemberSignature Language="VB.NET" Value="Public Property Image As String" />
      <MemberSignature Language="F#" Value="member this.Image : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.Container.Image" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.image")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7974d-115">取得またはコンテナー インスタンスを作成するために使用するイメージの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="7974d-115">Gets or sets the name of the image used to create the container instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceView">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerInstance.Models.ContainerPropertiesInstanceView InstanceView { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerInstance.Models.ContainerPropertiesInstanceView InstanceView" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.Container.InstanceView" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceView As ContainerPropertiesInstanceView" />
      <MemberSignature Language="F#" Value="member this.InstanceView : Microsoft.Azure.Management.ContainerInstance.Models.ContainerPropertiesInstanceView" Usage="Microsoft.Azure.Management.ContainerInstance.Models.Container.InstanceView" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.instanceView")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerInstance.Models.ContainerPropertiesInstanceView</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7974d-116">コンテナーのインスタンスのインスタンス ビューを取得します。</span><span class="sxs-lookup"><span data-stu-id="7974d-116">Gets the instance view of the container instance.</span></span> <span data-ttu-id="7974d-117">応答でのみ有効です。</span><span class="sxs-lookup"><span data-stu-id="7974d-117">Only valid in response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.Container.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.Container.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7974d-118">取得またはコンテナー インスタンスのユーザーが指定した名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="7974d-118">Gets or sets the user-provided name of the container instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ports">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort&gt; Ports { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort&gt; Ports" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.Container.Ports" />
      <MemberSignature Language="VB.NET" Value="Public Property Ports As IList(Of ContainerPort)" />
      <MemberSignature Language="F#" Value="member this.Ports : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.Container.Ports" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ports")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7974d-119">取得またはコンテナー インスタンスで公開されているポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="7974d-119">Gets or sets the exposed ports on the container instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resources">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements Resources { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements Resources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.Container.Resources" />
      <MemberSignature Language="VB.NET" Value="Public Property Resources As ResourceRequirements" />
      <MemberSignature Language="F#" Value="member this.Resources : Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.Container.Resources" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resources")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7974d-120">取得またはコンテナー インスタンスのリソース要件を設定します。</span><span class="sxs-lookup"><span data-stu-id="7974d-120">Gets or sets the resource requirements of the container instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.Container.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="container.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7974d-121">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="7974d-121">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7974d-122">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7974d-122">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VolumeMounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount&gt; VolumeMounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount&gt; VolumeMounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.Container.VolumeMounts" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeMounts As IList(Of VolumeMount)" />
      <MemberSignature Language="F#" Value="member this.VolumeMounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.Container.VolumeMounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.volumeMounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7974d-123">取得またはコンテナー インスタンスを使用可能なボリュームのマウントを設定します。</span><span class="sxs-lookup"><span data-stu-id="7974d-123">Gets or sets the volume mounts available to the container instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>