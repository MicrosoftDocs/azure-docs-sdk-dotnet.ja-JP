<Type Name="OperationImpact" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact">
  <TypeSignature Language="C#" Value="public class OperationImpact" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationImpact extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationImpact" />
  <TypeSignature Language="F#" Value="type OperationImpact = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            絶対パスと相対の両面で、操作の影響を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationImpact ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            OperationImpact クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationImpact (string name = null, string unit = null, Nullable&lt;double&gt; changeValueAbsolute = null, Nullable&lt;double&gt; changeValueRelative = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string unit, valuetype System.Nullable`1&lt;float64&gt; changeValueAbsolute, valuetype System.Nullable`1&lt;float64&gt; changeValueRelative) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact.#ctor(System.String,System.String,System.Nullable{System.Double},System.Nullable{System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional unit As String = null, Optional changeValueAbsolute As Nullable(Of Double) = null, Optional changeValueRelative As Nullable(Of Double) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact : string * string * Nullable&lt;double&gt; * Nullable&lt;double&gt; -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact (name, unit, changeValueAbsolute, changeValueRelative)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="changeValueAbsolute" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="changeValueRelative" Type="System.Nullable&lt;System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="name">影響のディメンションの名前。</param>
        <param name="unit">ディメンションへの影響を測定する単位の推定値。</param>
        <param name="changeValueAbsolute">ディメンションへの絶対への影響。</param>
        <param name="changeValueRelative">ディメンション (該当しない場合は null) に相対的影響</param>
        <summary>
            OperationImpact クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeValueAbsolute">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; ChangeValueAbsolute { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; ChangeValueAbsolute" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact.ChangeValueAbsolute" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ChangeValueAbsolute As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.ChangeValueAbsolute : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact.ChangeValueAbsolute" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="changeValueAbsolute")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ディメンションへの絶対の影響を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeValueRelative">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; ChangeValueRelative { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; ChangeValueRelative" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact.ChangeValueRelative" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ChangeValueRelative As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.ChangeValueRelative : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact.ChangeValueRelative" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="changeValueRelative")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ディメンションに対する相対的な影響を (該当しない場合は null) を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            影響のディメンションの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ディメンションへの影響を推定が値が測定単位を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>