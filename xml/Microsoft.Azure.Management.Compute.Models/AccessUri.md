<Type Name="AccessUri" FullName="Microsoft.Azure.Management.Compute.Models.AccessUri">
  <TypeSignature Language="C#" Value="public class AccessUri" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AccessUri extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.AccessUri" />
  <TypeSignature Language="VB.NET" Value="Public Class AccessUri" />
  <TypeSignature Language="F#" Value="type AccessUri = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="55b0f-101">ディスク アクセスの SAS uri。</span><span class="sxs-lookup"><span data-stu-id="55b0f-101">A disk access SAS uri.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessUri ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.AccessUri.#ctor" />
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
            <span data-ttu-id="55b0f-102">AccessUri クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="55b0f-102">Initializes a new instance of the AccessUri class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessUri (string accessSAS = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accessSAS) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.AccessUri.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional accessSAS As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.AccessUri : string -&gt; Microsoft.Azure.Management.Compute.Models.AccessUri" Usage="new Microsoft.Azure.Management.Compute.Models.AccessUri accessSAS" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accessSAS" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accessSAS"><span data-ttu-id="55b0f-103">ディスクにアクセスするための SAS uri。</span><span class="sxs-lookup"><span data-stu-id="55b0f-103">A SAS uri for accessing a disk.</span></span></param>
        <summary>
            <span data-ttu-id="55b0f-104">AccessUri クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="55b0f-104">Initializes a new instance of the AccessUri class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessSAS">
      <MemberSignature Language="C#" Value="public string AccessSAS { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccessSAS" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.AccessUri.AccessSAS" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessSAS As String" />
      <MemberSignature Language="F#" Value="member this.AccessSAS : string" Usage="Microsoft.Azure.Management.Compute.Models.AccessUri.AccessSAS" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.output.accessSAS")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55b0f-105">ディスクへのアクセスの SAS uri を取得します。</span><span class="sxs-lookup"><span data-stu-id="55b0f-105">Gets a SAS uri for accessing a disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>