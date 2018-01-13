<Type Name="OSDiskImage" FullName="Microsoft.Azure.Management.Compute.Models.OSDiskImage">
  <TypeSignature Language="C#" Value="public class OSDiskImage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OSDiskImage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.OSDiskImage" />
  <TypeSignature Language="VB.NET" Value="Public Class OSDiskImage" />
  <TypeSignature Language="F#" Value="type OSDiskImage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c5832-101">Os ディスクのイメージ情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c5832-101">Contains the os disk image information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OSDiskImage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.OSDiskImage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c5832-102">OSDiskImage クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c5832-102">Initializes a new instance of the OSDiskImage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OSDiskImage (Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes operatingSystem);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes operatingSystem) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.OSDiskImage.#ctor(Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (operatingSystem As OperatingSystemTypes)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.OSDiskImage : Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes -&gt; Microsoft.Azure.Management.Compute.Models.OSDiskImage" Usage="new Microsoft.Azure.Management.Compute.Models.OSDiskImage operatingSystem" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="operatingSystem" Type="Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes" />
      </Parameters>
      <Docs>
        <param name="operatingSystem"><span data-ttu-id="c5832-103">OsDiskImage のオペレーティング システム。</span><span class="sxs-lookup"><span data-stu-id="c5832-103">The operating system of the osDiskImage.</span></span> <span data-ttu-id="c5832-104">使用可能な値が含まれます 'Windows'、'Linux'。</span><span class="sxs-lookup"><span data-stu-id="c5832-104">Possible values include: 'Windows', 'Linux'</span></span></param>
        <summary>
            <span data-ttu-id="c5832-105">OSDiskImage クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c5832-105">Initializes a new instance of the OSDiskImage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperatingSystem">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes OperatingSystem { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes OperatingSystem" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSDiskImage.OperatingSystem" />
      <MemberSignature Language="VB.NET" Value="Public Property OperatingSystem As OperatingSystemTypes" />
      <MemberSignature Language="F#" Value="member this.OperatingSystem : Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSDiskImage.OperatingSystem" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operatingSystem")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c5832-106">取得または、osDiskImage のオペレーティング システムを設定します。</span><span class="sxs-lookup"><span data-stu-id="c5832-106">Gets or sets the operating system of the osDiskImage.</span></span> <span data-ttu-id="c5832-107">使用可能な値が含まれます 'Windows'、'Linux'。</span><span class="sxs-lookup"><span data-stu-id="c5832-107">Possible values include: 'Windows', 'Linux'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.OSDiskImage.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="oSDiskImage.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c5832-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="c5832-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c5832-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c5832-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>