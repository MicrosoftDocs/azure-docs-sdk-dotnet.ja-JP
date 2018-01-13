<Type Name="SharedKeyLiteTableCanonicalizer" FullName="Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer">
  <TypeSignature Language="C#" Value="public sealed class SharedKeyLiteTableCanonicalizer : Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedKeyLiteTableCanonicalizer extends System.Object implements class Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedKeyLiteTableCanonicalizer&#xA;Implements ICanonicalizer" />
  <TypeSignature Language="F#" Value="type SharedKeyLiteTableCanonicalizer = class&#xA;    interface ICanonicalizer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            テーブル サービスの共有キー Lite 認証スキームで署名するための適切な標準形式に HTTP 要求データを変換するカノニカライザーを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AuthorizationScheme">
      <MemberSignature Language="C#" Value="public string AuthorizationScheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer.AuthorizationScheme" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuthorizationScheme As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizationScheme : string" Usage="Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer.AuthorizationScheme" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer.AuthorizationScheme</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            正規化に使用する認証スキームを取得します。
            </summary>
        <value>正規化に使用する認証スキームです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanonicalizeHttpRequest">
      <MemberSignature Language="C#" Value="public string CanonicalizeHttpRequest (System.Net.HttpWebRequest request, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string CanonicalizeHttpRequest(class System.Net.HttpWebRequest request, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer.CanonicalizeHttpRequest(System.Net.HttpWebRequest,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CanonicalizeHttpRequest (request As HttpWebRequest, accountName As String) As String" />
      <MemberSignature Language="F#" Value="abstract member CanonicalizeHttpRequest : System.Net.HttpWebRequest * string -&gt; string&#xA;override this.CanonicalizeHttpRequest : System.Net.HttpWebRequest * string -&gt; string" Usage="sharedKeyLiteTableCanonicalizer.CanonicalizeHttpRequest (request, accountName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer.CanonicalizeHttpRequest(System.Net.HttpWebRequest,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.HttpWebRequest" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="request">HTTP 要求に署名する必要があります。</param>
        <param name="accountName">HTTP 要求にアクセスするストレージ アカウントの名前。</param>
        <summary>
            指定された HTTP 要求データを署名するための適切な標準形式に変換します。
            </summary>
        <returns>署名するための適切な標準形式の HTTP 要求データを含む正規化文字列です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Instance">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer Instance { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer Instance" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer.Instance" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Instance As SharedKeyLiteTableCanonicalizer" />
      <MemberSignature Language="F#" Value="member this.Instance : Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer" Usage="Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer.Instance" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            静的インスタンスを取得、<see cref="T:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer" />オブジェクト。
            </summary>
        <value>クラスの静的なインスタンス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>