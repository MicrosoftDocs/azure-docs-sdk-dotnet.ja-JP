<Type Name="EncryptionService" FullName="Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionService">
  <TypeSignature Language="C#" Value="public class EncryptionService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EncryptionService extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionService" />
  <TypeSignature Language="VB.NET" Value="Public Class EncryptionService" />
  <TypeSignature Language="F#" Value="type EncryptionService = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="be493-101">使用するサーバー側の暗号化を可能にするサービスです。</span><span class="sxs-lookup"><span data-stu-id="be493-101">A service that allows server-side encryption to be used.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="be493-102">EncryptionService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="be493-102">Initializes a new instance of the EncryptionService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionService (Nullable&lt;bool&gt; enabled = null, Nullable&lt;DateTime&gt; lastEnabledTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; enabled, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastEnabledTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionService.#ctor(System.Nullable{System.Boolean},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional enabled As Nullable(Of Boolean) = null, Optional lastEnabledTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionService : Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionService" Usage="new Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionService (enabled, lastEnabledTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="lastEnabledTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="enabled"><span data-ttu-id="be493-103">格納されているサービスがデータを暗号化するかどうかどうかを示すブール値。</span><span class="sxs-lookup"><span data-stu-id="be493-103">A boolean indicating whether or not the service encrypts the data as it is stored.</span></span></param>
        <param name="lastEnabledTime"><span data-ttu-id="be493-104">暗号化が有効、ユーザーが最後に日付/時刻の大まかな推定値を取得します。</span><span class="sxs-lookup"><span data-stu-id="be493-104">Gets a rough estimate of the date/time when the encryption was last enabled by the user.</span></span> <span data-ttu-id="be493-105">暗号化が有効な場合にのみ返されます。</span><span class="sxs-lookup"><span data-stu-id="be493-105">Only returned when encryption is enabled.</span></span> <span data-ttu-id="be493-106">大まかな推定値だけがこの時間後に書き込まれた一部の暗号化されていない blob がかかることがあります。</span><span class="sxs-lookup"><span data-stu-id="be493-106">There might be some unencrypted blobs which were written after this time, as it is just a rough estimate.</span></span></param>
        <summary>
            <span data-ttu-id="be493-107">EncryptionService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="be493-107">Initializes a new instance of the EncryptionService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionService.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionService.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be493-108">取得または格納されているサービスがデータを暗号化するかどうかを示すブール値を設定します。</span><span class="sxs-lookup"><span data-stu-id="be493-108">Gets or sets a boolean indicating whether or not the service encrypts the data as it is stored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastEnabledTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastEnabledTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastEnabledTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionService.LastEnabledTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastEnabledTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastEnabledTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionService.LastEnabledTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastEnabledTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be493-109">暗号化が有効、ユーザーが最後に日付/時刻の大まかな推定値を取得します。</span><span class="sxs-lookup"><span data-stu-id="be493-109">Gets a rough estimate of the date/time when the encryption was last enabled by the user.</span></span> <span data-ttu-id="be493-110">暗号化が有効な場合にのみ返されます。</span><span class="sxs-lookup"><span data-stu-id="be493-110">Only returned when encryption is enabled.</span></span>
            <span data-ttu-id="be493-111">大まかな推定値だけがこの時間後に書き込まれた一部の暗号化されていない blob がかかることがあります。</span><span class="sxs-lookup"><span data-stu-id="be493-111">There might be some unencrypted blobs which were written after this time, as it is just a rough estimate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>