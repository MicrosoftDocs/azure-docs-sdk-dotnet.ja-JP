<Type Name="Registry" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.Registry">
  <TypeSignature Language="C#" Value="public class Registry : Microsoft.Azure.Management.ContainerRegistry.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Registry extends Microsoft.Azure.Management.ContainerRegistry.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.Registry" />
  <TypeSignature Language="VB.NET" Value="Public Class Registry&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Registry = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ContainerRegistry.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            コンテナー レジストリを表すオブジェクト。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Registry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            レジストリ クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Registry (string location, Microsoft.Azure.Management.ContainerRegistry.Models.Sku sku, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string loginServer = null, Nullable&lt;DateTime&gt; creationDate = null, string provisioningState = null, Microsoft.Azure.Management.ContainerRegistry.Models.Status status = null, Nullable&lt;bool&gt; adminUserEnabled = null, Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties storageAccount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class Microsoft.Azure.Management.ContainerRegistry.Models.Sku sku, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string loginServer, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationDate, string provisioningState, class Microsoft.Azure.Management.ContainerRegistry.Models.Status status, valuetype System.Nullable`1&lt;bool&gt; adminUserEnabled, class Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.#ctor(System.String,Microsoft.Azure.Management.ContainerRegistry.Models.Sku,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{System.DateTime},System.String,Microsoft.Azure.Management.ContainerRegistry.Models.Status,System.Nullable{System.Boolean},Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.Registry : string * Microsoft.Azure.Management.ContainerRegistry.Models.Sku * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Management.ContainerRegistry.Models.Status * Nullable&lt;bool&gt; * Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Registry" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.Registry (location, sku, id, name, type, tags, loginServer, creationDate, provisioningState, status, adminUserEnabled, storageAccount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.ContainerRegistry.Models.Sku" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="loginServer" Type="System.String" />
        <Parameter Name="creationDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="status" Type="Microsoft.Azure.Management.ContainerRegistry.Models.Status" />
        <Parameter Name="adminUserEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="storageAccount" Type="Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties" />
      </Parameters>
      <Docs>
        <param name="location">リソースの場所です。 これは、リソースを作成した後に変更できません。</param>
        <param name="sku">コンテナー レジストリの SKU。</param>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前。</param>
        <param name="type">リソースの型。</param>
        <param name="tags">リソースのタグ。</param>
        <param name="loginServer">コンテナー レジストリにログインに使用できる URL。</param>
        <param name="creationDate">ISO8601 の形式でコンテナー レジストリの作成日。</param>
        <param name="provisioningState">時にコンテナー レジストリのプロビジョニングの状態、操作が呼び出されました。 使用可能な値が含まれます: '作成中'、'更新'、'削除'、'成功'、'失敗'、'キャンセル'</param>
        <param name="status">操作が呼び出された時にコンテナー レジストリのステータス。</param>
        <param name="adminUserEnabled">管理者ユーザーが有効になっているかどうかを示す値。</param>
        <param name="storageAccount">コンテナー レジストリのストレージ アカウントのプロパティです。 従来の SKU にのみ適用されます。</param>
        <summary>
            レジストリ クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUserEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AdminUserEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AdminUserEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.AdminUserEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUserEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AdminUserEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.AdminUserEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.adminUserEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または管理ユーザーが有効になっているかどうかを示す値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.CreationDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.CreationDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ISO8601 の形式でコンテナー レジストリの作成日を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoginServer">
      <MemberSignature Language="C#" Value="public string LoginServer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LoginServer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.LoginServer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoginServer As String" />
      <MemberSignature Language="F#" Value="member this.LoginServer : string" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.LoginServer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loginServer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンテナー レジストリにログインに使用できる URL を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            呼び出された操作時にコンテナー レジストリのプロビジョニングの状態を取得します。 使用可能な値が含まれます: '作成中'、'更新'、'削除'、'成功'、'失敗'、'キャンセル'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.ContainerRegistry.Models.Sku with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンテナー レジストリの SKU を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.Status Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.Status Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Status" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.ContainerRegistry.Models.Status" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Status</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            呼び出された操作時にコンテナー レジストリの状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties StorageAccount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties StorageAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.StorageAccount" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccount As StorageAccountProperties" />
      <MemberSignature Language="F#" Value="member this.StorageAccount : Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.StorageAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンテナー レジストリのストレージ アカウントのプロパティを設定します。 従来の SKU にのみ適用されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="registry.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>