<Type Name="Contact" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.Contact">
  <TypeSignature Language="C#" Value="public class Contact" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Contact extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.Contact" />
  <TypeSignature Language="VB.NET" Value="Public Class Contact" />
  <TypeSignature Language="F#" Value="type Contact = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ドメインの登録に情報を問い合わせてください。 ' ドメイン Privacy' オプションが選択されていない場合は、連絡先に関する情報が公開されている ICANN 要件に従った Whois ディレクトリをとおして利用可能な。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Contact ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.Contact.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            連絡先クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Contact (string email, string nameFirst, string nameLast, string phone, Microsoft.Azure.Management.AppService.Fluent.Models.Address addressMailing = null, string fax = null, string jobTitle = null, string nameMiddle = null, string organization = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string email, string nameFirst, string nameLast, string phone, class Microsoft.Azure.Management.AppService.Fluent.Models.Address addressMailing, string fax, string jobTitle, string nameMiddle, string organization) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.Contact.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.Address,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (email As String, nameFirst As String, nameLast As String, phone As String, Optional addressMailing As Address = null, Optional fax As String = null, Optional jobTitle As String = null, Optional nameMiddle As String = null, Optional organization As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.Contact : string * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.Address * string * string * string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.Contact" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.Contact (email, nameFirst, nameLast, phone, addressMailing, fax, jobTitle, nameMiddle, organization)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="email" Type="System.String" />
        <Parameter Name="nameFirst" Type="System.String" />
        <Parameter Name="nameLast" Type="System.String" />
        <Parameter Name="phone" Type="System.String" />
        <Parameter Name="addressMailing" Type="Microsoft.Azure.Management.AppService.Fluent.Models.Address" />
        <Parameter Name="fax" Type="System.String" />
        <Parameter Name="jobTitle" Type="System.String" />
        <Parameter Name="nameMiddle" Type="System.String" />
        <Parameter Name="organization" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="email">電子メール アドレス。</param>
        <param name="nameFirst">名。</param>
        <param name="nameLast">姓。</param>
        <param name="phone">電話番号です。</param>
        <param name="addressMailing">郵送先住所。</param>
        <param name="fax">Fax 番号です。</param>
        <param name="jobTitle">役職名。</param>
        <param name="nameMiddle">ミドル ネームです。</param>
        <param name="organization">組織。</param>
        <summary>
            連絡先クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddressMailing">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.Address AddressMailing { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.Address AddressMailing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.Contact.AddressMailing" />
      <MemberSignature Language="VB.NET" Value="Public Property AddressMailing As Address" />
      <MemberSignature Language="F#" Value="member this.AddressMailing : Microsoft.Azure.Management.AppService.Fluent.Models.Address with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.Contact.AddressMailing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="addressMailing")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.Address</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または郵送先住所を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Email">
      <MemberSignature Language="C#" Value="public string Email { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Email" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.Contact.Email" />
      <MemberSignature Language="VB.NET" Value="Public Property Email As String" />
      <MemberSignature Language="F#" Value="member this.Email : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.Contact.Email" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="email")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または電子メール アドレスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Fax">
      <MemberSignature Language="C#" Value="public string Fax { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Fax" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.Contact.Fax" />
      <MemberSignature Language="VB.NET" Value="Public Property Fax As String" />
      <MemberSignature Language="F#" Value="member this.Fax : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.Contact.Fax" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fax")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または fax 番号を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobTitle">
      <MemberSignature Language="C#" Value="public string JobTitle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobTitle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.Contact.JobTitle" />
      <MemberSignature Language="VB.NET" Value="Public Property JobTitle As String" />
      <MemberSignature Language="F#" Value="member this.JobTitle : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.Contact.JobTitle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobTitle")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または役職名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameFirst">
      <MemberSignature Language="C#" Value="public string NameFirst { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NameFirst" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.Contact.NameFirst" />
      <MemberSignature Language="VB.NET" Value="Public Property NameFirst As String" />
      <MemberSignature Language="F#" Value="member this.NameFirst : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.Contact.NameFirst" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nameFirst")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または姓を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameLast">
      <MemberSignature Language="C#" Value="public string NameLast { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NameLast" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.Contact.NameLast" />
      <MemberSignature Language="VB.NET" Value="Public Property NameLast As String" />
      <MemberSignature Language="F#" Value="member this.NameLast : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.Contact.NameLast" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nameLast")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または最後の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameMiddle">
      <MemberSignature Language="C#" Value="public string NameMiddle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NameMiddle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.Contact.NameMiddle" />
      <MemberSignature Language="VB.NET" Value="Public Property NameMiddle As String" />
      <MemberSignature Language="F#" Value="member this.NameMiddle : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.Contact.NameMiddle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nameMiddle")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはミドル ネームを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Organization">
      <MemberSignature Language="C#" Value="public string Organization { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Organization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.Contact.Organization" />
      <MemberSignature Language="VB.NET" Value="Public Property Organization As String" />
      <MemberSignature Language="F#" Value="member this.Organization : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.Contact.Organization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="organization")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または組織を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Phone">
      <MemberSignature Language="C#" Value="public string Phone { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Phone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.Contact.Phone" />
      <MemberSignature Language="VB.NET" Value="Public Property Phone As String" />
      <MemberSignature Language="F#" Value="member this.Phone : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.Contact.Phone" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="phone")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または電話番号を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.Contact.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="contact.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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