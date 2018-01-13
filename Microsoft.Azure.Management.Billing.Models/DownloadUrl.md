<Type Name="DownloadUrl" FullName="Microsoft.Azure.Management.Billing.Models.DownloadUrl">
  <TypeSignature Language="C#" Value="public class DownloadUrl" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DownloadUrl extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Billing.Models.DownloadUrl" />
  <TypeSignature Language="VB.NET" Value="Public Class DownloadUrl" />
  <TypeSignature Language="F#" Value="type DownloadUrl = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="25e37-101">PDF のダウンロードに使用することができますをセキュリティで保護された URL は、URL の有効期限が切れるまで請求書です。</span><span class="sxs-lookup"><span data-stu-id="25e37-101">A secure URL that can be used to download a PDF invoice until the URL expires.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DownloadUrl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.Models.DownloadUrl.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="25e37-102">DownloadUrl クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="25e37-102">Initializes a new instance of the DownloadUrl class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DownloadUrl (Nullable&lt;DateTime&gt; expiryTime = null, string url = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expiryTime, string url) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.Models.DownloadUrl.#ctor(System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional expiryTime As Nullable(Of DateTime) = null, Optional url As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Billing.Models.DownloadUrl : Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.Management.Billing.Models.DownloadUrl" Usage="new Microsoft.Azure.Management.Billing.Models.DownloadUrl (expiryTime, url)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="expiryTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="url" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="expiryTime"><span data-ttu-id="25e37-103">このダウンロード URL が期限切れになる UTC 時間です。</span><span class="sxs-lookup"><span data-stu-id="25e37-103">The time in UTC at which this download URL will expire.</span></span></param>
        <param name="url"><span data-ttu-id="25e37-104">PDF ファイルへの URL。</span><span class="sxs-lookup"><span data-stu-id="25e37-104">The URL to the PDF file.</span></span></param>
        <summary>
            <span data-ttu-id="25e37-105">DownloadUrl クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="25e37-105">Initializes a new instance of the DownloadUrl class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpiryTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpiryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Billing.Models.DownloadUrl.ExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiryTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpiryTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Billing.Models.DownloadUrl.ExpiryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="expiryTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25e37-106">このダウンロード URL が期限切れになる utc 時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="25e37-106">Gets the time in UTC at which this download URL will expire.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Billing.Models.DownloadUrl.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Management.Billing.Models.DownloadUrl.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25e37-107">PDF ファイルへの URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="25e37-107">Gets the URL to the PDF file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>