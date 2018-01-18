<Type Name="ResourceLimits" FullName="Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits">
  <TypeSignature Language="C#" Value="public class ResourceLimits" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceLimits extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceLimits" />
  <TypeSignature Language="F#" Value="type ResourceLimits = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e0688-101">リソースの制限。</span><span class="sxs-lookup"><span data-stu-id="e0688-101">The resource limits.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceLimits ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e0688-102">ResourceLimits クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e0688-102">Initializes a new instance of the ResourceLimits class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceLimits (Nullable&lt;double&gt; memoryInGB = null, Nullable&lt;double&gt; cpu = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;float64&gt; memoryInGB, valuetype System.Nullable`1&lt;float64&gt; cpu) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits.#ctor(System.Nullable{System.Double},System.Nullable{System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional memoryInGB As Nullable(Of Double) = null, Optional cpu As Nullable(Of Double) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits : Nullable&lt;double&gt; * Nullable&lt;double&gt; -&gt; Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits" Usage="new Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits (memoryInGB, cpu)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="memoryInGB" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="cpu" Type="System.Nullable&lt;System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="memoryInGB"><span data-ttu-id="e0688-103">このコンテナーのインスタンスの GB のメモリの上限。</span><span class="sxs-lookup"><span data-stu-id="e0688-103">The memory limit in GB of this container instance.</span></span></param>
        <param name="cpu"><span data-ttu-id="e0688-104">このコンテナーのインスタンスの CPU の制限。</span><span class="sxs-lookup"><span data-stu-id="e0688-104">The CPU limit of this container instance.</span></span></param>
        <summary>
            <span data-ttu-id="e0688-105">ResourceLimits クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e0688-105">Initializes a new instance of the ResourceLimits class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cpu">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Cpu { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Cpu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits.Cpu" />
      <MemberSignature Language="VB.NET" Value="Public Property Cpu As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Cpu : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits.Cpu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cpu")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0688-106">取得または、このコンテナーのインスタンスの CPU の制限を設定します。</span><span class="sxs-lookup"><span data-stu-id="e0688-106">Gets or sets the CPU limit of this container instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MemoryInGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MemoryInGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MemoryInGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits.MemoryInGB" />
      <MemberSignature Language="VB.NET" Value="Public Property MemoryInGB As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MemoryInGB : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ResourceLimits.MemoryInGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="memoryInGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0688-107">取得または gb このコンテナーのインスタンスのメモリの制限を設定します。</span><span class="sxs-lookup"><span data-stu-id="e0688-107">Gets or sets the memory limit in GB of this container instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>