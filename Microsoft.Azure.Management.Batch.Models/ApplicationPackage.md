<Type Name="ApplicationPackage" FullName="Microsoft.Azure.Management.Batch.Models.ApplicationPackage">
  <TypeSignature Language="C#" Value="public class ApplicationPackage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationPackage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.ApplicationPackage" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationPackage" />
  <TypeSignature Language="F#" Value="type ApplicationPackage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            アプリケーションの特定のバージョンを表すアプリケーション パッケージ。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationPackage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ApplicationPackage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ApplicationPackage クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationPackage (string id = null, string version = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.PackageState&gt; state = null, string format = null, string storageUrl = null, Nullable&lt;DateTime&gt; storageUrlExpiry = null, Nullable&lt;DateTime&gt; lastActivationTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string version, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.PackageState&gt; state, string format, string storageUrl, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; storageUrlExpiry, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastActivationTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ApplicationPackage.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.Batch.Models.PackageState},System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional version As String = null, Optional state As Nullable(Of PackageState) = null, Optional format As String = null, Optional storageUrl As String = null, Optional storageUrlExpiry As Nullable(Of DateTime) = null, Optional lastActivationTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.ApplicationPackage : string * string * Nullable&lt;Microsoft.Azure.Management.Batch.Models.PackageState&gt; * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.Batch.Models.ApplicationPackage" Usage="new Microsoft.Azure.Management.Batch.Models.ApplicationPackage (id, version, state, format, storageUrl, storageUrlExpiry, lastActivationTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.PackageState&gt;" />
        <Parameter Name="format" Type="System.String" />
        <Parameter Name="storageUrl" Type="System.String" />
        <Parameter Name="storageUrlExpiry" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastActivationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="id">アプリケーションの ID。</param>
        <param name="version">アプリケーション パッケージのバージョン。</param>
        <param name="state">アプリケーション パッケージの現在の状態。
            使用可能な値が含まれます: 'Pending'、'Active'、'マップされていない'</param>
        <param name="format">パッケージがアクティブな場合、アプリケーション パッケージの形式です。</param>
        <param name="storageUrl">Azure ストレージ内のアプリケーション パッケージの URL です。</param>
        <param name="storageUrlExpiry">Azure ストレージ URL が期限切れになる UTC 時間です。</param>
        <param name="lastActivationTime">パッケージが最後アクティブ化された、パッケージがアクティブな場合の時間。</param>
        <summary>
            ApplicationPackage クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public string Format { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ApplicationPackage.Format" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Format As String" />
      <MemberSignature Language="F#" Value="member this.Format : string" Usage="Microsoft.Azure.Management.Batch.Models.ApplicationPackage.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="format")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            パッケージがアクティブな場合は、アプリケーション パッケージの形式を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ApplicationPackage.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.Batch.Models.ApplicationPackage.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリケーションの ID を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastActivationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastActivationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastActivationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ApplicationPackage.LastActivationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastActivationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastActivationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.ApplicationPackage.LastActivationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastActivationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            パッケージがアクティブな場合に、パッケージが最後にアクティブに、時間を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.PackageState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.PackageState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ApplicationPackage.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of PackageState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Management.Batch.Models.PackageState&gt;" Usage="Microsoft.Azure.Management.Batch.Models.ApplicationPackage.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.PackageState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリケーション パッケージの現在の状態を取得します。 使用可能な値が含まれます: 'Pending'、'Active'、'マップされていない'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUrl">
      <MemberSignature Language="C#" Value="public string StorageUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ApplicationPackage.StorageUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUrl As String" />
      <MemberSignature Language="F#" Value="member this.StorageUrl : string" Usage="Microsoft.Azure.Management.Batch.Models.ApplicationPackage.StorageUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure ストレージにアプリケーション パッケージの URL を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUrlExpiry">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StorageUrlExpiry { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StorageUrlExpiry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ApplicationPackage.StorageUrlExpiry" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUrlExpiry As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StorageUrlExpiry : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.ApplicationPackage.StorageUrlExpiry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageUrlExpiry")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure ストレージ URL が期限切れになる UTC 時間を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ApplicationPackage.Version" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string" Usage="Microsoft.Azure.Management.Batch.Models.ApplicationPackage.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリケーション パッケージのバージョンを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>