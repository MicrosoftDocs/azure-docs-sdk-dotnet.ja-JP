<Type Name="LinuxConfiguration" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration">
  <TypeSignature Language="C#" Value="public class LinuxConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LinuxConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class LinuxConfiguration" />
  <TypeSignature Language="F#" Value="type LinuxConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8b6bb-101">OS プロファイルの Windows の構成について説明します。</span><span class="sxs-lookup"><span data-stu-id="8b6bb-101">Describes Windows configuration of the OS Profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinuxConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8b6bb-102">LinuxConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8b6bb-102">Initializes a new instance of the LinuxConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinuxConfiguration (Nullable&lt;bool&gt; disablePasswordAuthentication = null, Microsoft.Azure.Management.Compute.Fluent.Models.SshConfiguration ssh = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; disablePasswordAuthentication, class Microsoft.Azure.Management.Compute.Fluent.Models.SshConfiguration ssh) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration.#ctor(System.Nullable{System.Boolean},Microsoft.Azure.Management.Compute.Fluent.Models.SshConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional disablePasswordAuthentication As Nullable(Of Boolean) = null, Optional ssh As SshConfiguration = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration : Nullable&lt;bool&gt; * Microsoft.Azure.Management.Compute.Fluent.Models.SshConfiguration -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration (disablePasswordAuthentication, ssh)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="disablePasswordAuthentication" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ssh" Type="Microsoft.Azure.Management.Compute.Fluent.Models.SshConfiguration" />
      </Parameters>
      <Docs>
        <param name="disablePasswordAuthentication"><span data-ttu-id="8b6bb-103">パスワード認証を無効にするかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="8b6bb-103">Specifies whether password authentication should be disabled.</span></span></param>
        <param name="ssh"><span data-ttu-id="8b6bb-104">Linux Vm の SSH 構成します。</span><span class="sxs-lookup"><span data-stu-id="8b6bb-104">The SSH configuration for linux VMs.</span></span></param>
        <summary>
            <span data-ttu-id="8b6bb-105">LinuxConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8b6bb-105">Initializes a new instance of the LinuxConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisablePasswordAuthentication">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DisablePasswordAuthentication { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DisablePasswordAuthentication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration.DisablePasswordAuthentication" />
      <MemberSignature Language="VB.NET" Value="Public Property DisablePasswordAuthentication As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DisablePasswordAuthentication : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration.DisablePasswordAuthentication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="disablePasswordAuthentication")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b6bb-106">取得または設定は、パスワード認証を無効にするかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="8b6bb-106">Gets or sets specifies whether password authentication should be disabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ssh">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.SshConfiguration Ssh { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.SshConfiguration Ssh" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration.Ssh" />
      <MemberSignature Language="VB.NET" Value="Public Property Ssh As SshConfiguration" />
      <MemberSignature Language="F#" Value="member this.Ssh : Microsoft.Azure.Management.Compute.Fluent.Models.SshConfiguration with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration.Ssh" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ssh")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.SshConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b6bb-107">取得または linux 仮想マシンの SSH 構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="8b6bb-107">Gets or sets the SSH configuration for linux VMs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>