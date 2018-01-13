<Type Name="PublicClientApplication" FullName="Microsoft.Identity.Client.PublicClientApplication">
  <TypeSignature Language="C#" Value="public sealed class PublicClientApplication : Microsoft.Identity.Client.ClientApplicationBase, Microsoft.Identity.Client.IPublicClientApplication" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PublicClientApplication extends Microsoft.Identity.Client.ClientApplicationBase implements class Microsoft.Identity.Client.IClientApplicationBase, class Microsoft.Identity.Client.IPublicClientApplication" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.PublicClientApplication" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PublicClientApplication&#xA;Inherits ClientApplicationBase&#xA;Implements IPublicClientApplication" />
  <TypeSignature Language="F#" Value="type PublicClientApplication = class&#xA;    inherit ClientApplicationBase&#xA;    interface IPublicClientApplication&#xA;    interface IClientApplicationBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Identity.Client.ClientApplicationBase</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Identity.Client.IPublicClientApplication</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            ネイティブ アプリケーション (デスクトップ/UWP/iOS/Android) 用に使用するクラス。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PublicClientApplication (string clientId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.PublicClientApplication : string -&gt; Microsoft.Identity.Client.PublicClientApplication" Usage="new Microsoft.Identity.Client.PublicClientApplication clientId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId">アプリケーションのクライアント id</param>
        <summary>
            アプリケーションの Consutructor します。 既定の機関として https://login.microsoftonline.com/common が使用されます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PublicClientApplication (string clientId, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientId As String, authority As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.PublicClientApplication : string * string -&gt; Microsoft.Identity.Client.PublicClientApplication" Usage="new Microsoft.Identity.Client.PublicClientApplication (clientId, authority)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId">アプリケーションのクライアント id</param>
        <param name="authority">アプリケーションに使用する既定の機関</param>
        <summary>
            アプリケーションの Consutructor します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PublicClientApplication (string clientId, string authority, Microsoft.Identity.Client.TokenCache userTokenCache);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId, string authority, class Microsoft.Identity.Client.TokenCache userTokenCache) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.#ctor(System.String,System.String,Microsoft.Identity.Client.TokenCache)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientId As String, authority As String, userTokenCache As TokenCache)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.PublicClientApplication : string * string * Microsoft.Identity.Client.TokenCache -&gt; Microsoft.Identity.Client.PublicClientApplication" Usage="new Microsoft.Identity.Client.PublicClientApplication (clientId, authority, userTokenCache)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="userTokenCache" Type="Microsoft.Identity.Client.TokenCache" />
      </Parameters>
      <Docs>
        <param name="clientId">アプリケーションのクライアント id</param>
        <param name="authority">アプリケーションに使用する既定の機関</param>
        <param name="userTokenCache">TokenCache のインスタンス。</param>
        <summary>
            アプリケーション インスタンスを作成するコンス トラクターです。 このコンス トラクターは、デスクトップと NetCore アプリのみ
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String)) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync scopes" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <summary>
            対話型の要求トークンを取得します。 
            </summary>
        <returns>ユーザーのトークンを含む認証の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, user)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="user">Web UI で認証されるため、同じユーザーに適用するユーザー オブジェクトです。</param>
        <summary>
            対話型の要求トークンを取得します。 
            </summary>
        <returns>ユーザーのトークンを含む認証の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, parent)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UIParent)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="parent">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。 Xamarin.Android についてのみ必要です。</param>
        <summary>
            対話型の要求トークンを取得します。 
            </summary>
        <returns>ユーザーのトークンを含む認証の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, loginHint)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="loginHint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="loginHint">ユーザーの識別子です。 通常は UPN です。</param>
        <summary>
            対話型の要求トークンを取得します。 
            </summary>
        <returns>ユーザーのトークンを含む認証の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, user, parent)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIParent)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="user">Web UI で認証されるため、同じユーザーに適用するユーザー オブジェクトです。</param>
        <param name="parent">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。 Xamarin.Android についてのみ必要です。</param>
        <summary>
            対話型の要求トークンを取得します。 
            </summary>
        <returns>ユーザーのトークンを含む認証の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, loginHint, parent)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="loginHint">ユーザーの識別子です。 通常は UPN です。</param>
        <param name="parent">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。 Xamarin.Android についてのみ必要です。</param>
        <summary>
            対話型の要求トークンを取得します。 
            </summary>
        <returns>ユーザーのトークンを含む認証の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="user">Web UI で認証されるため、同じユーザーに適用するユーザー オブジェクトです。</param>
        <param name="behavior">UI の動作を制御する列挙体。</param>
        <param name="extraQueryParameters">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。 パラメーターを null にすることができます。</param>
        <summary>
            対話型の要求トークンを取得します。 
            </summary>
        <returns>ユーザーのトークンを含む認証の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="loginHint">ユーザーの識別子です。 通常は UPN です。</param>
        <param name="behavior">UI の動作を制御する列挙体。</param>
        <param name="extraQueryParameters">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。 パラメーターを null にすることができます。</param>
        <summary>
            対話型の要求トークンを取得します。 
            </summary>
        <returns>ユーザーのトークンを含む認証の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters, parent)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,Microsoft.Identity.Client.UIParent)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="user">Web UI で認証されるため、同じユーザーに適用するユーザー オブジェクトです。</param>
        <param name="behavior">UI の動作を制御する列挙体。</param>
        <param name="extraQueryParameters">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。 パラメーターを null にすることができます。</param>
        <param name="parent">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。 Xamarin.Android についてのみ必要です。</param>
        <summary>
            対話型の要求トークンを取得します。 
            </summary>
        <returns>ユーザーのトークンを含む認証の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters, parent)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,Microsoft.Identity.Client.UIParent)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="loginHint">ユーザーの識別子です。 通常は UPN です。</param>
        <param name="behavior">UI の動作を制御する列挙体。</param>
        <param name="extraQueryParameters">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。 パラメーターを null にすることができます。</param>
        <param name="parent">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。 Xamarin.Android についてのみ必要です。</param>
        <summary>
            対話型の要求トークンを取得します。 
            </summary>
        <returns>ユーザーのトークンを含む認証の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters, extraScopesToConsent, authority)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="user">Web UI で認証されるため、同じユーザーに適用するユーザー オブジェクトです。</param>
        <param name="behavior">UI の動作を制御する列挙体。</param>
        <param name="extraQueryParameters">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。 パラメーターを null にすることができます。</param>
        <param name="extraScopesToConsent">開発者があらかじめ同意を要求できますスコープの配列です。</param>
        <param name="authority">トークンの要求対象となる特定の機関です。 構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</param>
        <summary>
            対話型の要求トークンを取得します。 
            </summary>
        <returns>ユーザーのトークンを含む認証の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters, extraScopesToConsent, authority)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="loginHint">ユーザーの識別子です。 通常は UPN です。</param>
        <param name="behavior">UI の動作を制御する列挙体。</param>
        <param name="extraQueryParameters">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。 パラメーターを null にすることができます。</param>
        <param name="extraScopesToConsent">開発者があらかじめ同意を要求できますスコープの配列です。</param>
        <param name="authority">トークンの要求対象となる特定の機関です。 構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</param>
        <summary>
            対話型の要求トークンを取得します。 
            </summary>
        <returns>ユーザーのトークンを含む認証の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters, extraScopesToConsent, authority, parent)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="user">Web UI で認証されるため、同じユーザーに適用するユーザー オブジェクトです。</param>
        <param name="behavior">UI の動作を制御する列挙体。</param>
        <param name="extraQueryParameters">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。 パラメーターを null にすることができます。</param>
        <param name="extraScopesToConsent">開発者があらかじめ同意を要求できますスコープの配列です。</param>
        <param name="authority">トークンの要求対象となる特定の機関です。 構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</param>
        <param name="parent">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。 Xamarin.Android についてのみ必要です。</param>
        <summary>
            対話型の要求トークンを取得します。 
            </summary>
        <returns>ユーザーのトークンを含む認証の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.PublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="publicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters, extraScopesToConsent, authority, parent)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.PublicClientApplication/&lt;AcquireTokenAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="loginHint">ユーザーの識別子です。 通常は UPN です。</param>
        <param name="behavior">UI の動作を制御する列挙体。</param>
        <param name="extraQueryParameters">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。 パラメーターを null にすることができます。</param>
        <param name="extraScopesToConsent">開発者があらかじめ同意を要求できますスコープの配列です。</param>
        <param name="authority">トークンの要求対象となる特定の機関です。 構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</param>
        <param name="parent">オブジェクトには、親ウィンドウ/アクティビティへの参照が含まれています。 Xamarin.Android についてのみ必要です。</param>
        <summary>
            対話型の要求トークンを取得します。 
            </summary>
        <returns>ユーザーのトークンを含む認証の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>