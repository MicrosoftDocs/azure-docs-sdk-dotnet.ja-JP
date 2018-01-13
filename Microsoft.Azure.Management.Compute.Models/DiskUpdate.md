<Type Name="DiskUpdate" FullName="Microsoft.Azure.Management.Compute.Models.DiskUpdate">
  <TypeSignature Language="C#" Value="public class DiskUpdate : Microsoft.Azure.Management.Compute.Models.ResourceUpdate" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DiskUpdate extends Microsoft.Azure.Management.Compute.Models.ResourceUpdate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.DiskUpdate" />
  <TypeSignature Language="VB.NET" Value="Public Class DiskUpdate&#xA;Inherits ResourceUpdate" />
  <TypeSignature Language="F#" Value="type DiskUpdate = class&#xA;    inherit ResourceUpdate" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Models.ResourceUpdate</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            ディスクの更新リソースです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiskUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.DiskUpdate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DiskUpdate クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiskUpdate (System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Compute.Models.DiskSku sku = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; osType = null, Nullable&lt;int&gt; diskSizeGB = null, Microsoft.Azure.Management.Compute.Models.EncryptionSettings encryptionSettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Compute.Models.DiskSku sku, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; osType, valuetype System.Nullable`1&lt;int32&gt; diskSizeGB, class Microsoft.Azure.Management.Compute.Models.EncryptionSettings encryptionSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.DiskUpdate.#ctor(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Compute.Models.DiskSku,System.Nullable{Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes},System.Nullable{System.Int32},Microsoft.Azure.Management.Compute.Models.EncryptionSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.DiskUpdate : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Compute.Models.DiskSku * Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.Compute.Models.EncryptionSettings -&gt; Microsoft.Azure.Management.Compute.Models.DiskUpdate" Usage="new Microsoft.Azure.Management.Compute.Models.DiskUpdate (tags, sku, osType, diskSizeGB, encryptionSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Compute.Models.DiskSku" />
        <Parameter Name="osType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt;" />
        <Parameter Name="diskSizeGB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="encryptionSettings" Type="Microsoft.Azure.Management.Compute.Models.EncryptionSettings" />
      </Parameters>
      <Docs>
        <param name="tags">リソース タグ</param>
        <param name="sku">To be added.</param>
        <param name="osType">オペレーティング システムの種類。 使用可能な値が含まれます 'Windows'、'Linux'。</param>
        <param name="diskSizeGB">CreationData.createOption が空の場合は、このフィールドは必須およびを作成する VHD のサイズを示します。 このフィールドが更新プログラムやその他のオプションを使用した作成用に存在する場合は、サイズ変更を示します。 サイズ変更はディスクが実行中の VM にアタッチされていないと、ディスクのサイズを増やすことができますのみ場合のみ使用できます。</param>
        <param name="encryptionSettings">ディスクまたはスナップショットの暗号化の設定</param>
        <summary>
            DiskUpdate クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DiskSizeGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DiskSizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.DiskUpdate.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeGB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.DiskUpdate.DiskSizeGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.diskSizeGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定 creationData.createOption が空では、このフィールドは必須および作成する VHD のサイズを示す場合。 このフィールドが更新プログラムやその他のオプションを使用した作成用に存在する場合は、サイズ変更を示します。 サイズ変更はディスクが実行中の VM にアタッチされていないと、ディスクのサイズを増やすことができますのみ場合のみ使用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.EncryptionSettings EncryptionSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.EncryptionSettings EncryptionSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.DiskUpdate.EncryptionSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionSettings As EncryptionSettings" />
      <MemberSignature Language="F#" Value="member this.EncryptionSettings : Microsoft.Azure.Management.Compute.Models.EncryptionSettings with get, set" Usage="Microsoft.Azure.Management.Compute.Models.DiskUpdate.EncryptionSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.EncryptionSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定のディスクまたはスナップショットの暗号化の設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.DiskUpdate.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As Nullable(Of OperatingSystemTypes)" />
      <MemberSignature Language="F#" Value="member this.OsType : Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.DiskUpdate.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.osType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはオペレーティング システムの種類を設定します。 使用可能な値が含まれます 'Windows'、'Linux'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.DiskUpdate.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="diskUpdate.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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