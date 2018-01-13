<Type Name="SetRouteConstraint&lt;TSet&gt;" FullName="Microsoft.Azure.Mobile.Server.Config.SetRouteConstraint&lt;TSet&gt;">
  <TypeSignature Language="C#" Value="public class SetRouteConstraint&lt;TSet&gt; : System.Web.Http.Routing.IHttpRouteConstraint" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SetRouteConstraint`1&lt;TSet&gt; extends System.Object implements class System.Web.Http.Routing.IHttpRouteConstraint" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Config.SetRouteConstraint`1" />
  <TypeSignature Language="VB.NET" Value="Public Class SetRouteConstraint(Of TSet)&#xA;Implements IHttpRouteConstraint" />
  <TypeSignature Language="F#" Value="type SetRouteConstraint&lt;'Set&gt; = class&#xA;    interface IHttpRouteConstraint" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TSet" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Web.Http.Routing.IHttpRouteConstraint</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TSet">一連の包含または除外する値の型。</typeparam>
    <summary>
            含まれているまたは型の値のセットから除外するか、ルート パラメーター値を規定するルート制約<typeparamref name="TSet" />です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SetRouteConstraint (System.Collections.Generic.HashSet&lt;TSet&gt; set, bool matchOnExcluded);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.HashSet`1&lt;!TSet&gt; set, bool matchOnExcluded) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.SetRouteConstraint`1.#ctor(System.Collections.Generic.HashSet{`0},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (set As HashSet(Of TSet), matchOnExcluded As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Config.SetRouteConstraint&lt;'Set&gt; : System.Collections.Generic.HashSet&lt;'Set&gt; * bool -&gt; Microsoft.Azure.Mobile.Server.Config.SetRouteConstraint&lt;'Set&gt;" Usage="new Microsoft.Azure.Mobile.Server.Config.SetRouteConstraint&lt;'Set&gt; (set, matchOnExcluded)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="set" Type="System.Collections.Generic.HashSet&lt;TSet&gt;" />
        <Parameter Name="matchOnExcluded" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="set">照合する値のセット。</param>
        <param name="matchOnExcluded">パラメーターの値を含まれているかセットから除外することを示します。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Mobile.Server.Config.SetRouteConstraint`1" /> クラスの新しいインスタンスを初期化します。 使用して、<paramref name="matchOnExcluded" />制約に含まれているか、値の指定されたセットから除外するパラメーターの値が必要かどうかを示すためにします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Excluded">
      <MemberSignature Language="C#" Value="public bool Excluded { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Excluded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Config.SetRouteConstraint`1.Excluded" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Excluded As Boolean" />
      <MemberSignature Language="F#" Value="member this.Excluded : bool" Usage="Microsoft.Azure.Mobile.Server.Config.SetRouteConstraint&lt;'Set&gt;.Excluded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            一致するパラメーター名を含まれているかに一致するために設定されている値で排除されたかどうかを示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Match">
      <MemberSignature Language="C#" Value="public bool Match (System.Net.Http.HttpRequestMessage request, System.Web.Http.Routing.IHttpRoute route, string parameterName, System.Collections.Generic.IDictionary&lt;string,object&gt; values, System.Web.Http.Routing.HttpRouteDirection routeDirection);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Match(class System.Net.Http.HttpRequestMessage request, class System.Web.Http.Routing.IHttpRoute route, string parameterName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; values, valuetype System.Web.Http.Routing.HttpRouteDirection routeDirection) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.SetRouteConstraint`1.Match(System.Net.Http.HttpRequestMessage,System.Web.Http.Routing.IHttpRoute,System.String,System.Collections.Generic.IDictionary{System.String,System.Object},System.Web.Http.Routing.HttpRouteDirection)" />
      <MemberSignature Language="VB.NET" Value="Public Function Match (request As HttpRequestMessage, route As IHttpRoute, parameterName As String, values As IDictionary(Of String, Object), routeDirection As HttpRouteDirection) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Match : System.Net.Http.HttpRequestMessage * System.Web.Http.Routing.IHttpRoute * string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * System.Web.Http.Routing.HttpRouteDirection -&gt; bool&#xA;override this.Match : System.Net.Http.HttpRequestMessage * System.Web.Http.Routing.IHttpRoute * string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * System.Web.Http.Routing.HttpRouteDirection -&gt; bool" Usage="setRouteConstraint.Match (request, route, parameterName, values, routeDirection)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Web.Http.Routing.IHttpRouteConstraint.Match(System.Net.Http.HttpRequestMessage,System.Web.Http.Routing.IHttpRoute,System.String,System.Collections.Generic.IDictionary{System.String,System.Object},System.Web.Http.Routing.HttpRouteDirection)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="route" Type="System.Web.Http.Routing.IHttpRoute" />
        <Parameter Name="parameterName" Type="System.String" />
        <Parameter Name="values" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="routeDirection" Type="System.Web.Http.Routing.HttpRouteDirection" />
      </Parameters>
      <Docs>
        <param name="request">To be added.</param>
        <param name="route">To be added.</param>
        <param name="parameterName">To be added.</param>
        <param name="values">To be added.</param>
        <param name="routeDirection">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="Set">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.HashSet&lt;TSet&gt; Set { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.HashSet`1&lt;!TSet&gt; Set" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Config.SetRouteConstraint`1.Set" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Set As HashSet(Of TSet)" />
      <MemberSignature Language="F#" Value="member this.Set : System.Collections.Generic.HashSet&lt;'Set&gt;" Usage="Microsoft.Azure.Mobile.Server.Config.SetRouteConstraint&lt;'Set&gt;.Set" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.HashSet&lt;TSet&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            除外されるか、含まれる値のセットを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>