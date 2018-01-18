<Type Name="GcmCredential" FullName="Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential">
  <TypeSignature Language="C#" Value="public class GcmCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GcmCredential extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class GcmCredential" />
  <TypeSignature Language="F#" Value="type GcmCredential = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f7808-101">NotificationHub GcmCredential の説明です。</span><span class="sxs-lookup"><span data-stu-id="f7808-101">Description of a NotificationHub GcmCredential.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GcmCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7808-102">GcmCredential クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f7808-102">Initializes a new instance of the GcmCredential class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GcmCredential (string gcmEndpoint = null, string googleApiKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string gcmEndpoint, string googleApiKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional gcmEndpoint As String = null, Optional googleApiKey As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential : string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential (gcmEndpoint, googleApiKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="gcmEndpoint" Type="System.String" />
        <Parameter Name="googleApiKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="gcmEndpoint"><span data-ttu-id="f7808-103">GCM エンドポイントです。</span><span class="sxs-lookup"><span data-stu-id="f7808-103">The GCM endpoint.</span></span></param>
        <param name="googleApiKey"><span data-ttu-id="f7808-104">Google API キー。</span><span class="sxs-lookup"><span data-stu-id="f7808-104">The Google API key.</span></span></param>
        <summary>
            <span data-ttu-id="f7808-105">GcmCredential クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f7808-105">Initializes a new instance of the GcmCredential class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GcmEndpoint">
      <MemberSignature Language="C#" Value="public string GcmEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GcmEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential.GcmEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property GcmEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.GcmEndpoint : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential.GcmEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.gcmEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7808-106">取得または GCM エンドポイントを設定します。</span><span class="sxs-lookup"><span data-stu-id="f7808-106">Gets or sets the GCM endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GoogleApiKey">
      <MemberSignature Language="C#" Value="public string GoogleApiKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GoogleApiKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential.GoogleApiKey" />
      <MemberSignature Language="VB.NET" Value="Public Property GoogleApiKey As String" />
      <MemberSignature Language="F#" Value="member this.GoogleApiKey : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential.GoogleApiKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.googleApiKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7808-107">取得または Google API キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="f7808-107">Gets or sets the Google API key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>