<Type Name="SasQueryBuilder" FullName="Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder">
  <TypeSignature Language="C#" Value="public class SasQueryBuilder : Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SasQueryBuilder extends Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class SasQueryBuilder&#xA;Inherits UriQueryBuilder" />
  <TypeSignature Language="F#" Value="type SasQueryBuilder = class&#xA;    inherit UriQueryBuilder" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            特定の SAS URI クエリ文字列を構築するための便利なクラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SasQueryBuilder (string sasToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sasToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sasToken As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder : string -&gt; Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder" Usage="new Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder sasToken" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sasToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sasToken">要求を認証するために使用する ASA トークンです。</param>
        <summary>
            パブリック SasQueryBuilder コンス トラクターです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public override void Add (string name, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Add(string name, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder.Add(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Add (name As String, value As String)" />
      <MemberSignature Language="F#" Value="override this.Add : string * string -&gt; unit" Usage="sasQueryBuilder.Add (name, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">クエリ文字列名。</param>
        <param name="value">クエリ文字列の値。</param>
        <summary>
            URI のエスケープとクエリ文字列の値を追加します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddToUri">
      <MemberSignature Language="C#" Value="public override Uri AddToUri (Uri uri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Uri AddToUri(class System.Uri uri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder.AddToUri(System.Uri)" />
      <MemberSignature Language="F#" Value="override this.AddToUri : Uri -&gt; Uri" Usage="sasQueryBuilder.AddToUri uri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />既存のクエリ パラメーターを含む元の URI を含むオブジェクト。</param>
        <summary>
            URI にクエリ パラメーターを追加します。
            </summary>
        <returns>A<see cref="T:System.Uri" />オブジェクトを新しいクエリ パラメーターが追加されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequireHttps">
      <MemberSignature Language="C#" Value="public bool RequireHttps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequireHttps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder.RequireHttps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequireHttps As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequireHttps : bool" Usage="Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder.RequireHttps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Https をパラメーターのいずれかを指定する場合は True を返します。 します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>