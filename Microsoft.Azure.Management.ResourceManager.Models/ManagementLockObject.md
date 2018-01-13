<Type Name="ManagementLockObject" FullName="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject">
  <TypeSignature Language="C#" Value="public class ManagementLockObject : Microsoft.Rest.Azure.IResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManagementLockObject extends System.Object implements class Microsoft.Rest.Azure.IResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
  <TypeSignature Language="VB.NET" Value="Public Class ManagementLockObject&#xA;Implements IResource" />
  <TypeSignature Language="F#" Value="type ManagementLockObject = class&#xA;    interface IResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Rest.Azure.IResource</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            ロックの情報です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementLockObject ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ManagementLockObject クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementLockObject (string level, string notes = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockOwner&gt; owners = null, string id = null, string type = null, string name = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string level, string notes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockOwner&gt; owners, string id, string type, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockOwner},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (level As String, Optional notes As String = null, Optional owners As IList(Of ManagementLockOwner) = null, Optional id As String = null, Optional type As String = null, Optional name As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockOwner&gt; * string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject (level, notes, owners, id, type, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="level" Type="System.String" />
        <Parameter Name="notes" Type="System.String" />
        <Parameter Name="owners" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockOwner&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="level">ロックのレベルです。 指定できる値は: NotSpecified、CanNotDelete、読み取り専用です。 CanNotDelete では、承認されたユーザーは読み取ると、リソースを変更するは削除することを意味します。
            読み取り専用では、承認されたユーザーは、リソースからのみ読み取ることができますが、変更または削除することはできませんを意味します。 使用可能な値が含まれます: 'NotSpecified'、'CanNotDelete'、'ReadOnly'</param>
        <param name="notes">ロックに関する注意事項です。 最大 512 文字です。</param>
        <param name="owners">ロックの所有者。</param>
        <param name="id">ロックのリソース ID です。</param>
        <param name="type">ロックの Microsoft.Authorization/locks のリソースの種類。</param>
        <param name="name">ロックの名前。</param>
        <summary>
            ManagementLockObject クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            ロックのリソース ID を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public string Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Level" />
      <MemberSignature Language="VB.NET" Value="Public Property Level As String" />
      <MemberSignature Language="F#" Value="member this.Level : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.level")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはロックのレベルを設定します。 指定できる値は: NotSpecified、CanNotDelete、読み取り専用です。 CanNotDelete では、承認されたユーザーは読み取ると、リソースを変更するは削除することを意味します。
            読み取り専用では、承認されたユーザーは、リソースからのみ読み取ることができますが、変更または削除することはできませんを意味します。 使用可能な値が含まれます: 'NotSpecified'、'CanNotDelete'、'ReadOnly'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはロックの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Notes">
      <MemberSignature Language="C#" Value="public string Notes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Notes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Notes" />
      <MemberSignature Language="VB.NET" Value="Public Property Notes As String" />
      <MemberSignature Language="F#" Value="member this.Notes : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Notes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.notes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはロックに関する注意事項を設定します。 最大 512 文字です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Owners">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockOwner&gt; Owners { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockOwner&gt; Owners" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Owners" />
      <MemberSignature Language="VB.NET" Value="Public Property Owners As IList(Of ManagementLockOwner)" />
      <MemberSignature Language="F#" Value="member this.Owners : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockOwner&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Owners" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.owners")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockOwner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはロックの所有者を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ロック - Microsoft.Authorization/locks のリソースの種類を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="managementLockObject.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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