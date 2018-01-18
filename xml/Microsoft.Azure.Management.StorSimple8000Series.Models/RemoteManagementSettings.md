<Type Name="RemoteManagementSettings" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings">
  <TypeSignature Language="C#" Value="public class RemoteManagementSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RemoteManagementSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class RemoteManagementSettings" />
  <TypeSignature Language="F#" Value="type RemoteManagementSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f82dd-101">デバイスのリモート管理の設定。</span><span class="sxs-lookup"><span data-stu-id="f82dd-101">The settings for remote management of a device.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RemoteManagementSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f82dd-102">RemoteManagementSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f82dd-102">Initializes a new instance of the RemoteManagementSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RemoteManagementSettings (Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementModeConfiguration remoteManagementMode, string remoteManagementCertificate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementModeConfiguration remoteManagementMode, string remoteManagementCertificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementModeConfiguration,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (remoteManagementMode As RemoteManagementModeConfiguration, Optional remoteManagementCertificate As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementModeConfiguration * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings (remoteManagementMode, remoteManagementCertificate)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="remoteManagementMode" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementModeConfiguration" />
        <Parameter Name="remoteManagementCertificate" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="remoteManagementMode"><span data-ttu-id="f82dd-103">リモート管理モードです。</span><span class="sxs-lookup"><span data-stu-id="f82dd-103">The remote management mode.</span></span>
            <span data-ttu-id="f82dd-104">使用可能な値が含まれます: 'Unknown'、'無効'、'HttpsEnabled'、'HttpsAndHttpEnabled'</span><span class="sxs-lookup"><span data-stu-id="f82dd-104">Possible values include: 'Unknown', 'Disabled', 'HttpsEnabled', 'HttpsAndHttpEnabled'</span></span></param>
        <param name="remoteManagementCertificate"><span data-ttu-id="f82dd-105">リモート管理証明書。</span><span class="sxs-lookup"><span data-stu-id="f82dd-105">The remote management certificates.</span></span></param>
        <summary>
            <span data-ttu-id="f82dd-106">RemoteManagementSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f82dd-106">Initializes a new instance of the RemoteManagementSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteManagementCertificate">
      <MemberSignature Language="C#" Value="public string RemoteManagementCertificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemoteManagementCertificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings.RemoteManagementCertificate" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteManagementCertificate As String" />
      <MemberSignature Language="F#" Value="member this.RemoteManagementCertificate : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings.RemoteManagementCertificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="remoteManagementCertificate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f82dd-107">取得またはリモート管理証明書を設定します。</span><span class="sxs-lookup"><span data-stu-id="f82dd-107">Gets or sets the remote management certificates.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteManagementMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementModeConfiguration RemoteManagementMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementModeConfiguration RemoteManagementMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings.RemoteManagementMode" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteManagementMode As RemoteManagementModeConfiguration" />
      <MemberSignature Language="F#" Value="member this.RemoteManagementMode : Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementModeConfiguration with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings.RemoteManagementMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="remoteManagementMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementModeConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f82dd-108">取得またはリモート管理モードを設定します。</span><span class="sxs-lookup"><span data-stu-id="f82dd-108">Gets or sets the remote management mode.</span></span> <span data-ttu-id="f82dd-109">使用可能な値が含まれます: 'Unknown'、'無効'、'HttpsEnabled'、'HttpsAndHttpEnabled'</span><span class="sxs-lookup"><span data-stu-id="f82dd-109">Possible values include: 'Unknown', 'Disabled', 'HttpsEnabled', 'HttpsAndHttpEnabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="remoteManagementSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f82dd-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f82dd-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f82dd-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f82dd-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>