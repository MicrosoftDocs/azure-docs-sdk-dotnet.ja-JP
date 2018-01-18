<Type Name="VolumeMount" FullName="Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount">
  <TypeSignature Language="C#" Value="public class VolumeMount" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VolumeMount extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount" />
  <TypeSignature Language="VB.NET" Value="Public Class VolumeMount" />
  <TypeSignature Language="F#" Value="type VolumeMount = class" />
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
            <span data-ttu-id="8a233-101">ボリュームのプロパティをマウントします。</span><span class="sxs-lookup"><span data-stu-id="8a233-101">The properties of the volume mount.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VolumeMount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8a233-102">VolumeMount クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8a233-102">Initializes a new instance of the VolumeMount class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VolumeMount (string name, string mountPath, Nullable&lt;bool&gt; readOnlyProperty = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string mountPath, valuetype System.Nullable`1&lt;bool&gt; readOnlyProperty) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount.#ctor(System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, mountPath As String, Optional readOnlyProperty As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount : string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount" Usage="new Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount (name, mountPath, readOnlyProperty)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="mountPath" Type="System.String" />
        <Parameter Name="readOnlyProperty" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="8a233-103">ボリュームのマウントの名前。</span><span class="sxs-lookup"><span data-stu-id="8a233-103">The name of the volume mount.</span></span></param>
        <param name="mountPath"><span data-ttu-id="8a233-104">ボリュームのマウントされているコンテナー内のパス。</span><span class="sxs-lookup"><span data-stu-id="8a233-104">The path within the container where the volume should be mounted.</span></span> <span data-ttu-id="8a233-105">コロン (:) が含まれていない必要があります。</span><span class="sxs-lookup"><span data-stu-id="8a233-105">Must not contain colon (:).</span></span></param>
        <param name="readOnlyProperty"><span data-ttu-id="8a233-106">ボリュームのマウントは読み取り専用であるかどうかを示すフラグ。</span><span class="sxs-lookup"><span data-stu-id="8a233-106">The flag indicating whether the volume mount is read-only.</span></span></param>
        <summary>
            <span data-ttu-id="8a233-107">VolumeMount クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8a233-107">Initializes a new instance of the VolumeMount class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MountPath">
      <MemberSignature Language="C#" Value="public string MountPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MountPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount.MountPath" />
      <MemberSignature Language="VB.NET" Value="Public Property MountPath As String" />
      <MemberSignature Language="F#" Value="member this.MountPath : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount.MountPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mountPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a233-108">取得またはボリュームのマウントされているコンテナー内のパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="8a233-108">Gets or sets the path within the container where the volume should be mounted.</span></span> <span data-ttu-id="8a233-109">コロン (:) が含まれていない必要があります。</span><span class="sxs-lookup"><span data-stu-id="8a233-109">Must not contain colon (:).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount.Name" />
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
            <span data-ttu-id="8a233-110">取得またはボリュームのマウントの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="8a233-110">Gets or sets the name of the volume mount.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadOnlyProperty">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ReadOnlyProperty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ReadOnlyProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount.ReadOnlyProperty" />
      <MemberSignature Language="VB.NET" Value="Public Property ReadOnlyProperty As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ReadOnlyProperty : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount.ReadOnlyProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="readOnly")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a233-111">取得またはボリュームのマウントは読み取り専用であるかどうかを示すフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="8a233-111">Gets or sets the flag indicating whether the volume mount is read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="volumeMount.Validate " />
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
            <span data-ttu-id="8a233-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="8a233-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8a233-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a233-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>