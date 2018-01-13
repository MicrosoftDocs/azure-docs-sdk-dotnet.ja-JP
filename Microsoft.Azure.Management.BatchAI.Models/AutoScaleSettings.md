<Type Name="AutoScaleSettings" FullName="Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings">
  <TypeSignature Language="C#" Value="public class AutoScaleSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoScaleSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoScaleSettings" />
  <TypeSignature Language="F#" Value="type AutoScaleSettings = class" />
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
            <span data-ttu-id="abf58-101">システムは、上下 (minimumNodeCount maximumNodeCount 内) に基づくクラスター、クラスターで保留中と実行中のジョブを自動的にスケーリングします。</span><span class="sxs-lookup"><span data-stu-id="abf58-101">The system automatically scales the cluster up and down (within minimumNodeCount and maximumNodeCount) based on the pending and running jobs on the cluster.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoScaleSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="abf58-102">AutoScaleSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="abf58-102">Initializes a new instance of the AutoScaleSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoScaleSettings (int minimumNodeCount, int maximumNodeCount, Nullable&lt;int&gt; initialNodeCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 minimumNodeCount, int32 maximumNodeCount, valuetype System.Nullable`1&lt;int32&gt; initialNodeCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings.#ctor(System.Int32,System.Int32,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (minimumNodeCount As Integer, maximumNodeCount As Integer, Optional initialNodeCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings : int * int * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings" Usage="new Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings (minimumNodeCount, maximumNodeCount, initialNodeCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="minimumNodeCount" Type="System.Int32" />
        <Parameter Name="maximumNodeCount" Type="System.Int32" />
        <Parameter Name="initialNodeCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="minimumNodeCount"><span data-ttu-id="abf58-103">クラスターが持つことができます、コンピューティング ノードの最小数を指定します。</span><span class="sxs-lookup"><span data-stu-id="abf58-103">Specifies the minimum number of compute nodes the cluster can have.</span></span></param>
        <param name="maximumNodeCount"><span data-ttu-id="abf58-104">クラスターが持つことができます、コンピューティング ノードの最大数を指定します。</span><span class="sxs-lookup"><span data-stu-id="abf58-104">Specifies the maximum number of compute nodes the cluster can have.</span></span></param>
        <param name="initialNodeCount"><span data-ttu-id="abf58-105">クラスターの作成に割り当てるコンピューティング ノードの数を指定します。</span><span class="sxs-lookup"><span data-stu-id="abf58-105">Specifies the number of compute nodes to allocate on cluster creation.</span></span> <span data-ttu-id="abf58-106">この値は クラスターの作成中にのみ使用されていることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="abf58-106">Note that this value is used only during cluster creation.</span></span></param>
        <summary>
            <span data-ttu-id="abf58-107">AutoScaleSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="abf58-107">Initializes a new instance of the AutoScaleSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialNodeCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; InitialNodeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; InitialNodeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings.InitialNodeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialNodeCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.InitialNodeCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings.InitialNodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="initialNodeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="abf58-108">取得または設定は、クラスターの作成に割り当てるコンピューティング ノードの数を指定します。</span><span class="sxs-lookup"><span data-stu-id="abf58-108">Gets or sets specifies the number of compute nodes to allocate on cluster creation.</span></span> <span data-ttu-id="abf58-109">この値は クラスターの作成中にのみ使用されていることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="abf58-109">Note that this value is used only during cluster creation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNodeCount">
      <MemberSignature Language="C#" Value="public int MaximumNodeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaximumNodeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings.MaximumNodeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumNodeCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaximumNodeCount : int with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings.MaximumNodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maximumNodeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="abf58-110">取得または設定は、クラスターのコンピューティング ノードの最大数を指定します。</span><span class="sxs-lookup"><span data-stu-id="abf58-110">Gets or sets specifies the maximum number of compute nodes the cluster can have.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumNodeCount">
      <MemberSignature Language="C#" Value="public int MinimumNodeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MinimumNodeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings.MinimumNodeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MinimumNodeCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MinimumNodeCount : int with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings.MinimumNodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minimumNodeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="abf58-111">取得または設定は、クラスターのコンピューティング ノードの最小数を指定します。</span><span class="sxs-lookup"><span data-stu-id="abf58-111">Gets or sets specifies the minimum number of compute nodes the cluster can have.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="autoScaleSettings.Validate " />
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
            <span data-ttu-id="abf58-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="abf58-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="abf58-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="abf58-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>