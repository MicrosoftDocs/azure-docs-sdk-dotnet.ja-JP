<Type Name="CDataMember" FullName="Microsoft.Azure.NotificationHubs.CDataMember">
  <TypeSignature Language="C#" Value="public sealed class CDataMember : System.Xml.Serialization.IXmlSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CDataMember extends System.Object implements class System.Xml.Serialization.IXmlSerializable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.CDataMember" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CDataMember&#xA;Implements IXmlSerializable" />
  <TypeSignature Language="F#" Value="type CDataMember = class&#xA;    interface IXmlSerializable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Xml.Serialization.IXmlSerializable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Xml.Serialization.XmlSchemaProvider("GenerateSchema")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>通知を表す、<see cref="T:Microsoft.Azure.NotificationHubs.CDataMember" />です。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CDataMember ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.CDataMember.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.CDataMember" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CDataMember (string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.CDataMember.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (value As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.CDataMember : string -&gt; Microsoft.Azure.NotificationHubs.CDataMember" Usage="new Microsoft.Azure.NotificationHubs.CDataMember value" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="value">指定した値。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.CDataMember" />指定の値を持つクラス。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateSchema">
      <MemberSignature Language="C#" Value="public static System.Xml.XmlQualifiedName GenerateSchema (System.Xml.Schema.XmlSchemaSet xs);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Xml.XmlQualifiedName GenerateSchema(class System.Xml.Schema.XmlSchemaSet xs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.CDataMember.GenerateSchema(System.Xml.Schema.XmlSchemaSet)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateSchema (xs As XmlSchemaSet) As XmlQualifiedName" />
      <MemberSignature Language="F#" Value="static member GenerateSchema : System.Xml.Schema.XmlSchemaSet -&gt; System.Xml.XmlQualifiedName" Usage="Microsoft.Azure.NotificationHubs.CDataMember.GenerateSchema xs" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.XmlQualifiedName</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="xs" Type="System.Xml.Schema.XmlSchemaSet" />
      </Parameters>
      <Docs>
        <param name="xs">XML スキーマです。</param>
        <summary>XML スキーマの変換のスキーマ表現が生成されます。</summary>
        <returns>XML スキーマの変換のスキーマ表現。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSchema">
      <MemberSignature Language="C#" Value="public System.Xml.Schema.XmlSchema GetSchema ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Xml.Schema.XmlSchema GetSchema() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.CDataMember.GetSchema" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSchema () As XmlSchema" />
      <MemberSignature Language="F#" Value="abstract member GetSchema : unit -&gt; System.Xml.Schema.XmlSchema&#xA;override this.GetSchema : unit -&gt; System.Xml.Schema.XmlSchema" Usage="cDataMember.GetSchema " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.GetSchema</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.Schema.XmlSchema</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>XML スキーマをスキーマ表現を返します。</summary>
        <returns>XML スキーマをスキーマ表現。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Implicit">
      <MemberSignature Language="C#" Value="public static implicit operator string (Microsoft.Azure.NotificationHubs.CDataMember value);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname string op_Implicit(class Microsoft.Azure.NotificationHubs.CDataMember value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.CDataMember.op_Implicit(Microsoft.Azure.NotificationHubs.CDataMember)~System.String" />
      <MemberSignature Language="VB.NET" Value="Public Shared Widening Operator CType (value As CDataMember) As String" />
      <MemberSignature Language="F#" Value="static member op_Implicit : Microsoft.Azure.NotificationHubs.CDataMember -&gt; string" Usage="Microsoft.Azure.NotificationHubs.CDataMember.op_Implicit value" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value" Type="Microsoft.Azure.NotificationHubs.CDataMember" />
      </Parameters>
      <Docs>
        <param name="value">変換する値。</param>
        <summary>指定した値を変換、<see cref="T:Microsoft.Azure.NotificationHubs.CDataMember" />オブジェクト。</summary>
        <returns>値に変換するため、<see cref="T:Microsoft.Azure.NotificationHubs.CDataMember" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Implicit">
      <MemberSignature Language="C#" Value="public static implicit operator Microsoft.Azure.NotificationHubs.CDataMember (string value);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname class Microsoft.Azure.NotificationHubs.CDataMember op_Implicit(string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.CDataMember.op_Implicit(System.String)~Microsoft.Azure.NotificationHubs.CDataMember" />
      <MemberSignature Language="VB.NET" Value="Public Shared Widening Operator CType (value As String) As CDataMember" />
      <MemberSignature Language="F#" Value="static member op_Implicit : string -&gt; Microsoft.Azure.NotificationHubs.CDataMember" Usage="Microsoft.Azure.NotificationHubs.CDataMember.op_Implicit value" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.CDataMember</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="value">変換する値。</param>
        <summary>変換、<see cref="T:Microsoft.Azure.NotificationHubs.CDataMember" />オブジェクトを指定した値にします。</summary>
        <returns>変換された<see cref="T:Microsoft.Azure.NotificationHubs.CDataMember" />オブジェクトを指定した値にします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadXml">
      <MemberSignature Language="C#" Value="public void ReadXml (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReadXml(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.CDataMember.ReadXml(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReadXml (reader As XmlReader)" />
      <MemberSignature Language="F#" Value="abstract member ReadXml : System.Xml.XmlReader -&gt; unit&#xA;override this.ReadXml : System.Xml.XmlReader -&gt; unit" Usage="cDataMember.ReadXml reader" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.ReadXml(System.Xml.XmlReader)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader">データを読み取る XML リーダーです。</param>
        <summary>XML 形式から XML スキーマを読み込みます。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.CDataMember.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="cDataMember.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>現在のオブジェクトを表す文字列を返します。</summary>
        <returns>現在のオブジェクトを表す文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.CDataMember.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.NotificationHubs.CDataMember.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定の値、<see cref="T:Microsoft.Azure.NotificationHubs.CDataMember" />です。</summary>
        <value><see cref="T:Microsoft.Azure.NotificationHubs.CDataMember" /> の値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteXml">
      <MemberSignature Language="C#" Value="public void WriteXml (System.Xml.XmlWriter writer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void WriteXml(class System.Xml.XmlWriter writer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.CDataMember.WriteXml(System.Xml.XmlWriter)" />
      <MemberSignature Language="VB.NET" Value="Public Sub WriteXml (writer As XmlWriter)" />
      <MemberSignature Language="F#" Value="abstract member WriteXml : System.Xml.XmlWriter -&gt; unit&#xA;override this.WriteXml : System.Xml.XmlWriter -&gt; unit" Usage="cDataMember.WriteXml writer" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.WriteXml(System.Xml.XmlWriter)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
      </Parameters>
      <Docs>
        <param name="writer">記述する XML ライター。</param>
        <summary>XML 表現に XML データを書き込みます。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>