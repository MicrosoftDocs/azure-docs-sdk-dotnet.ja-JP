<Type Name="TileText" FullName="Microsoft.Azure.Mobile.Server.TileText">
  <TypeSignature Language="C#" Value="public class TileText" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TileText extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.TileText" />
  <TypeSignature Language="VB.NET" Value="Public Class TileText" />
  <TypeSignature Language="F#" Value="type TileText = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            このクラスを表します、<c>テキスト</c>Windows Notification タイルの要素を参照してください<c>http://msdn.microsoft.com/en-us/library/windows/apps/hh761491.aspx</c>詳細についてはします。
            このクラスは、の一部として使用するものでは、<see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TileText ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TileText.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public int Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileText.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As Integer" />
      <MemberSignature Language="F#" Value="member this.Id : int with get, set" Usage="Microsoft.Azure.Mobile.Server.TileText.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このテキストは、タイル テンプレート内のテキスト要素。 テンプレートに 1 つだけのテキスト要素がある場合は、この値は 1 です。 利用可能なテキストの位置の数は、テンプレートの定義に基づきます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lang">
      <MemberSignature Language="C#" Value="public string Lang { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Lang" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileText.Lang" />
      <MemberSignature Language="VB.NET" Value="Public Property Lang As String" />
      <MemberSignature Language="F#" Value="member this.Lang : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileText.Lang" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("lang")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Bcp-47 の言語などのタグとして指定された XML ペイロードの対象となるロケール<c>EN-US</c>または<c>FR-FR</c>です。 ここで指定されたロケールでは、任意の他の指定されたロケール、バインディングまたはビジュアルになどをオーバーライドします。 この値がリテラル文字列の場合は、この属性の既定値であるユーザーの UI 言語が使用します。 この値が文字列の参照の場合は、この属性の既定値は、文字列の解決に、Windows ランタイムによって選択されたロケールにします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Text">
      <MemberSignature Language="C#" Value="public string Text { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Text" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileText.Text" />
      <MemberSignature Language="VB.NET" Value="Public Property Text As String" />
      <MemberSignature Language="F#" Value="member this.Text : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileText.Text" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlText</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タイルの要素の実際のテキスト。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>