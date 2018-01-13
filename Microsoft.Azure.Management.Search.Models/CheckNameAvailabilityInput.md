<Type Name="CheckNameAvailabilityInput" FullName="Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityInput">
  <TypeSignature Language="C#" Value="public class CheckNameAvailabilityInput" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi CheckNameAvailabilityInput extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityInput" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckNameAvailabilityInput" />
  <TypeSignature Language="F#" Value="type CheckNameAvailabilityInput = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            名前の可用性をチェック API の入力です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityInput ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityInput.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            CheckNameAvailabilityInput クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityInput (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityInput.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityInput : string -&gt; Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityInput" Usage="new Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityInput name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">検証する検索サービスの名前。 検索サービス名は、小文字、数字、ダッシュのみを含める必要があります、最初の 2 つ、または最後の 1 文字としてダッシュを使用することはできません、連続するダッシュ文字を含めることはできません、および 2 ~ 60 文字の長さの間である必要がありますをします。</param>
        <summary>
            CheckNameAvailabilityInput クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityInput.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityInput.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
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
            取得または設定の検索サービス名を検証します。 検索サービス名は、小文字、数字、ダッシュのみを含める必要があります、最初の 2 つ、または最後の 1 文字としてダッシュを使用することはできません、連続するダッシュ文字を含めることはできません、および 2 ~ 60 文字の長さの間である必要がありますをします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public static string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityInput.Type" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityInput.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
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
            リソースの名前を検証する対象の型。 この値は、'searchServices' を常にする必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityInput.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="checkNameAvailabilityInput.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
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