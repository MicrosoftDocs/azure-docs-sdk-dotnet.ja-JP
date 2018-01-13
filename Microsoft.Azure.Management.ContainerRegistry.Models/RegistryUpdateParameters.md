<Type Name="RegistryUpdateParameters" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters">
  <TypeSignature Language="C#" Value="public class RegistryUpdateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RegistryUpdateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class RegistryUpdateParameters" />
  <TypeSignature Language="F#" Value="type RegistryUpdateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
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
            コンテナー レジストリを更新するためのパラメーターです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegistryUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            RegistryUpdateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegistryUpdateParameters (System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.ContainerRegistry.Models.Sku sku = null, Nullable&lt;bool&gt; adminUserEnabled = null, Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties storageAccount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.ContainerRegistry.Models.Sku sku, valuetype System.Nullable`1&lt;bool&gt; adminUserEnabled, class Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.#ctor(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.ContainerRegistry.Models.Sku,System.Nullable{System.Boolean},Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.ContainerRegistry.Models.Sku * Nullable&lt;bool&gt; * Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters (tags, sku, adminUserEnabled, storageAccount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.ContainerRegistry.Models.Sku" />
        <Parameter Name="adminUserEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="storageAccount" Type="Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties" />
      </Parameters>
      <Docs>
        <param name="tags">コンテナー レジストリのタグ。</param>
        <param name="sku">コンテナー レジストリの SKU。</param>
        <param name="adminUserEnabled">管理者ユーザーが有効になっているかどうかを示す値。</param>
        <param name="storageAccount">コンテナー レジストリのストレージ アカウントのパラメーターです。 従来の SKU にのみ適用されます。 指定した場合、ストレージ アカウント コンテナー レジストリと同じ物理的な場所にする必要があります。</param>
        <summary>
            RegistryUpdateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUserEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AdminUserEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AdminUserEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.AdminUserEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUserEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AdminUserEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.AdminUserEnabled" />
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
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.ContainerRegistry.Models.Sku with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.Sku" />
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
    <Member MemberName="StorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties StorageAccount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties StorageAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.StorageAccount" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccount As StorageAccountProperties" />
      <MemberSignature Language="F#" Value="member this.StorageAccount : Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.StorageAccount" />
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
            取得またはコンテナー レジストリのストレージ アカウントのパラメーターを設定します。 従来の SKU にのみ適用されます。 指定した場合、ストレージ アカウント コンテナー レジストリと同じ物理的な場所にする必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンテナー レジストリにタグを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="registryUpdateParameters.Validate " />
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