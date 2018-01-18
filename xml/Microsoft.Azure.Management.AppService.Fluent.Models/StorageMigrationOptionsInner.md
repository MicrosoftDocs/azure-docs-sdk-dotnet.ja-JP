<Type Name="StorageMigrationOptionsInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.StorageMigrationOptionsInner">
  <TypeSignature Language="C#" Value="public class StorageMigrationOptionsInner : Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageMigrationOptionsInner extends Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.StorageMigrationOptionsInner" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageMigrationOptionsInner&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type StorageMigrationOptionsInner = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="0108c-101">アプリのコンテンツの移行のオプションです。</span><span class="sxs-lookup"><span data-stu-id="0108c-101">Options for app content migration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageMigrationOptionsInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.StorageMigrationOptionsInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0108c-102">StorageMigrationOptionsInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0108c-102">Initializes a new instance of the StorageMigrationOptionsInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageMigrationOptionsInner (string id = null, string name = null, string kind = null, string type = null, string azurefilesConnectionString = null, string azurefilesShare = null, Nullable&lt;bool&gt; switchSiteAfterMigration = null, Nullable&lt;bool&gt; blockWriteAccessToSite = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string azurefilesConnectionString, string azurefilesShare, valuetype System.Nullable`1&lt;bool&gt; switchSiteAfterMigration, valuetype System.Nullable`1&lt;bool&gt; blockWriteAccessToSite) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.StorageMigrationOptionsInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional azurefilesConnectionString As String = null, Optional azurefilesShare As String = null, Optional switchSiteAfterMigration As Nullable(Of Boolean) = null, Optional blockWriteAccessToSite As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.StorageMigrationOptionsInner : string * string * string * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.StorageMigrationOptionsInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.StorageMigrationOptionsInner (id, name, kind, type, azurefilesConnectionString, azurefilesShare, switchSiteAfterMigration, blockWriteAccessToSite)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="azurefilesConnectionString" Type="System.String" />
        <Parameter Name="azurefilesShare" Type="System.String" />
        <Parameter Name="switchSiteAfterMigration" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="blockWriteAccessToSite" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="kind">To be added.</param>
        <param name="type">To be added.</param>
        <param name="azurefilesConnectionString">To be added.</param>
        <param name="azurefilesShare">To be added.</param>
        <param name="switchSiteAfterMigration">To be added.</param>
        <param name="blockWriteAccessToSite">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzurefilesConnectionString">
      <MemberSignature Language="C#" Value="public string AzurefilesConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzurefilesConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.StorageMigrationOptionsInner.AzurefilesConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property AzurefilesConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.AzurefilesConnectionString : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.StorageMigrationOptionsInner.AzurefilesConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.azurefilesConnectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0108c-103">取得または azureFiles 接続文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="0108c-103">Gets or sets azureFiles connection string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzurefilesShare">
      <MemberSignature Language="C#" Value="public string AzurefilesShare { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzurefilesShare" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.StorageMigrationOptionsInner.AzurefilesShare" />
      <MemberSignature Language="VB.NET" Value="Public Property AzurefilesShare As String" />
      <MemberSignature Language="F#" Value="member this.AzurefilesShare : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.StorageMigrationOptionsInner.AzurefilesShare" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.azurefilesShare")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0108c-104">取得または azureFiles 共有を設定します。</span><span class="sxs-lookup"><span data-stu-id="0108c-104">Gets or sets azureFiles share.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlockWriteAccessToSite">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; BlockWriteAccessToSite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; BlockWriteAccessToSite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.StorageMigrationOptionsInner.BlockWriteAccessToSite" />
      <MemberSignature Language="VB.NET" Value="Public Property BlockWriteAccessToSite As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.BlockWriteAccessToSite : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.StorageMigrationOptionsInner.BlockWriteAccessToSite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.blockWriteAccessToSite")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0108c-105">取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; コピー操作中にのみ読み取り、それ以外に、アプリがある場合&amp;lt; コード&amp;gt; false&amp;lt;/code。&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="0108c-105">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if the app should be read only during copy operation; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SwitchSiteAfterMigration">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SwitchSiteAfterMigration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SwitchSiteAfterMigration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.StorageMigrationOptionsInner.SwitchSiteAfterMigration" />
      <MemberSignature Language="VB.NET" Value="Public Property SwitchSiteAfterMigration As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SwitchSiteAfterMigration : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.StorageMigrationOptionsInner.SwitchSiteAfterMigration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.switchSiteAfterMigration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0108c-106">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; を、それ以外のアプリを切り替える必要がありますと&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="0108c-106">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt;if the app should be switched over; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>