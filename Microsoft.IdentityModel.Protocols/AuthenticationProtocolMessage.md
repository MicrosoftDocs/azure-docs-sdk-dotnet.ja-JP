<Type Name="AuthenticationProtocolMessage" FullName="Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage">
  <TypeSignature Language="C#" Value="public abstract class AuthenticationProtocolMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit AuthenticationProtocolMessage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class AuthenticationProtocolMessage" />
  <TypeSignature Language="F#" Value="type AuthenticationProtocolMessage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
    <AssemblyVersion>2.1.3.0</AssemblyVersion>
    <AssemblyVersion>5.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            認証プロトコル メッセージの基本クラス。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected AuthenticationProtocolMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            既定のインスタンスを初期化、<see cref="T:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage" />クラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildFormPost">
      <MemberSignature Language="C#" Value="public virtual string BuildFormPost ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string BuildFormPost() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.BuildFormPost" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BuildFormPost () As String" />
      <MemberSignature Language="F#" Value="abstract member BuildFormPost : unit -&gt; string&#xA;override this.BuildFormPost : unit -&gt; string" Usage="authenticationProtocolMessage.BuildFormPost " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在の IssuerAddress と設定されているパラメーターを使用してフォーム ポストを構築します。
            </summary>
        <returns>head で html 設定 'Title'、本文を含む、hiden からアクション = IssuerAddress です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildRedirectUrl">
      <MemberSignature Language="C#" Value="public virtual string BuildRedirectUrl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string BuildRedirectUrl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.BuildRedirectUrl" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BuildRedirectUrl () As String" />
      <MemberSignature Language="F#" Value="abstract member BuildRedirectUrl : unit -&gt; string&#xA;override this.BuildRedirectUrl : unit -&gt; string" Usage="authenticationProtocolMessage.BuildRedirectUrl " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在の IssuerAddress と設定されているパラメーターを使用して Url を構築します。
            </summary>
        <returns>エンコードの文字列です。</returns>
        <remarks>各パラメーター&lt;キー、値&gt;を使用して変換は、まず<see cref="M:System.Uri.EscapeDataString(System.String)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetParameter">
      <MemberSignature Language="C#" Value="public virtual string GetParameter (string parameter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetParameter(string parameter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.GetParameter(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetParameter (parameter As String) As String" />
      <MemberSignature Language="F#" Value="abstract member GetParameter : string -&gt; string&#xA;override this.GetParameter : string -&gt; string" Usage="authenticationProtocolMessage.GetParameter parameter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parameter">パラメーターの名前。</param>
        <summary>
            パラメーターを返します。
            </summary>
        <returns>パラメーターまたはパラメーターでない場合は null の値が存在します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">パラメーターが null の場合</exception>
      </Docs>
    </Member>
    <Member MemberName="IssuerAddress">
      <MemberSignature Language="C#" Value="public string IssuerAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IssuerAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.IssuerAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property IssuerAddress As String" />
      <MemberSignature Language="F#" Value="member this.IssuerAddress : string with get, set" Usage="Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.IssuerAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            発行者のアドレスを取得または設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">'Value' が null の場合は。</exception>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ディクショナリとしてのメッセージのパラメーターを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostTitle">
      <MemberSignature Language="C#" Value="public string PostTitle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PostTitle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.PostTitle" />
      <MemberSignature Language="VB.NET" Value="Public Property PostTitle As String" />
      <MemberSignature Language="F#" Value="member this.PostTitle : string with get, set" Usage="Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.PostTitle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または送信文字列を構築するときに使用されるタイトルを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">'Value' が null の場合は。</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveParameter">
      <MemberSignature Language="C#" Value="public virtual void RemoveParameter (string parameter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveParameter(string parameter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.RemoveParameter(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub RemoveParameter (parameter As String)" />
      <MemberSignature Language="F#" Value="abstract member RemoveParameter : string -&gt; unit&#xA;override this.RemoveParameter : string -&gt; unit" Usage="authenticationProtocolMessage.RemoveParameter parameter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parameter">パラメーターの名前。</param>
        <summary>
            パラメーターを削除します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">'Parameter' が null または空の場合は。</exception>
      </Docs>
    </Member>
    <Member MemberName="ScriptButtonText">
      <MemberSignature Language="C#" Value="public string ScriptButtonText { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptButtonText" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.ScriptButtonText" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptButtonText As String" />
      <MemberSignature Language="F#" Value="member this.ScriptButtonText : string with get, set" Usage="Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.ScriptButtonText" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または post 文字列を構築するときに使用されるスクリプトのボタンのテキストを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">'Value' が null の場合は。</exception>
      </Docs>
    </Member>
    <Member MemberName="ScriptDisabledText">
      <MemberSignature Language="C#" Value="public string ScriptDisabledText { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptDisabledText" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.ScriptDisabledText" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptDisabledText As String" />
      <MemberSignature Language="F#" Value="member this.ScriptDisabledText : string with get, set" Usage="Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.ScriptDisabledText" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはスクリプトが無効になっている場合に使用される表示される post 文字列を構築するときに使用されるテキストを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">'Value' が null の場合は。</exception>
      </Docs>
    </Member>
    <Member MemberName="SetParameter">
      <MemberSignature Language="C#" Value="public void SetParameter (string parameter, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetParameter(string parameter, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.SetParameter(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetParameter (parameter As String, value As String)" />
      <MemberSignature Language="F#" Value="member this.SetParameter : string * string -&gt; unit" Usage="authenticationProtocolMessage.SetParameter (parameter, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameter" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parameter">パラメーターの名前。</param>
        <param name="value">パラメーターに割り当てられる値です。</param>
        <summary>
            パラメーターをパラメーター ディクショナリに設定します。
            </summary>
        <remarks>値として null が渡されるパラメーターが存在する場合は、そのパラメーターが削除されます。</remarks>
        <exception cref="T:System.ArgumentNullException">'ParameterName' が null または空の場合は。</exception>
      </Docs>
    </Member>
    <Member MemberName="SetParameters">
      <MemberSignature Language="C#" Value="public virtual void SetParameters (System.Collections.Specialized.NameValueCollection nameValueCollection);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetParameters(class System.Collections.Specialized.NameValueCollection nameValueCollection) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.SetParameters(System.Collections.Specialized.NameValueCollection)" />
      <MemberSignature Language="F#" Value="abstract member SetParameters : System.Collections.Specialized.NameValueCollection -&gt; unit&#xA;override this.SetParameters : System.Collections.Specialized.NameValueCollection -&gt; unit" Usage="authenticationProtocolMessage.SetParameters nameValueCollection" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nameValueCollection" Type="System.Collections.Specialized.NameValueCollection" />
      </Parameters>
      <Docs>
        <param name="nameValueCollection"></param>
        <summary>
            コレクションにパラメーターを設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>