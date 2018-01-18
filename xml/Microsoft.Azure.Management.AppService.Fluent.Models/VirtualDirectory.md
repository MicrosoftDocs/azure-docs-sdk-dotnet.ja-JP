<Type Name="VirtualDirectory" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.VirtualDirectory">
  <TypeSignature Language="C#" Value="public class VirtualDirectory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualDirectory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.VirtualDirectory" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualDirectory" />
  <TypeSignature Language="F#" Value="type VirtualDirectory = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1ca62-101">仮想アプリケーションのディレクトリです。</span><span class="sxs-lookup"><span data-stu-id="1ca62-101">Directory for virtual application.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualDirectory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.VirtualDirectory.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1ca62-102">VirtualDirectory クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1ca62-102">Initializes a new instance of the VirtualDirectory class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualDirectory (string virtualPath = null, string physicalPath = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string virtualPath, string physicalPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.VirtualDirectory.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional virtualPath As String = null, Optional physicalPath As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.VirtualDirectory : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.VirtualDirectory" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.VirtualDirectory (virtualPath, physicalPath)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="virtualPath" Type="System.String" />
        <Parameter Name="physicalPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="virtualPath"><span data-ttu-id="1ca62-103">仮想アプリケーションへのパス。</span><span class="sxs-lookup"><span data-stu-id="1ca62-103">Path to virtual application.</span></span></param>
        <param name="physicalPath"><span data-ttu-id="1ca62-104">物理パス。</span><span class="sxs-lookup"><span data-stu-id="1ca62-104">Physical path.</span></span></param>
        <summary>
            <span data-ttu-id="1ca62-105">VirtualDirectory クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1ca62-105">Initializes a new instance of the VirtualDirectory class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PhysicalPath">
      <MemberSignature Language="C#" Value="public string PhysicalPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PhysicalPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.VirtualDirectory.PhysicalPath" />
      <MemberSignature Language="VB.NET" Value="Public Property PhysicalPath As String" />
      <MemberSignature Language="F#" Value="member this.PhysicalPath : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.VirtualDirectory.PhysicalPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="physicalPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ca62-106">取得または物理パスを設定します。</span><span class="sxs-lookup"><span data-stu-id="1ca62-106">Gets or sets physical path.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualPath">
      <MemberSignature Language="C#" Value="public string VirtualPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.VirtualDirectory.VirtualPath" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualPath As String" />
      <MemberSignature Language="F#" Value="member this.VirtualPath : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.VirtualDirectory.VirtualPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ca62-107">取得または仮想のアプリケーションへのパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="1ca62-107">Gets or sets path to virtual application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>