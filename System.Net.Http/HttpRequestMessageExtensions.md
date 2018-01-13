<Type Name="HttpRequestMessageExtensions" FullName="System.Net.Http.HttpRequestMessageExtensions">
  <TypeSignature Language="C#" Value="public static class HttpRequestMessageExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit HttpRequestMessageExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Net.Http.HttpRequestMessageExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module HttpRequestMessageExtensions" />
  <TypeSignature Language="F#" Value="type HttpRequestMessageExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            拡張メソッドを<see cref="T:System.Net.Http.HttpRequestMessage" />さまざまなユーティリティを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateBadRequestResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateBadRequestResponse (this System.Net.Http.HttpRequestMessage request);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateBadRequestResponse(class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateBadRequestResponse(System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateBadRequestResponse (request As HttpRequestMessage) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateBadRequestResponse : System.Net.Http.HttpRequestMessage -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateBadRequestResponse request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
      </Parameters>
      <Docs>
        <param name="request">現在の <see cref="T:System.Net.Http.HttpRequestMessage" /> です。</param>
        <summary>
            作成、<see cref="T:System.Net.Http.HttpResponseMessage" />で、<see cref="F:System.Net.HttpStatusCode.BadRequest" />ステータス コードと、既定値<see cref="T:System.Web.Http.HttpError" />として HTTP 応答本文です。
            </summary>
        <returns>初期化された<see cref="T:System.Net.Http.HttpResponseMessage" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBadRequestResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateBadRequestResponse (this System.Net.Http.HttpRequestMessage request, string format, params object[] args);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateBadRequestResponse(class System.Net.Http.HttpRequestMessage request, string format, object[] args) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateBadRequestResponse(System.Net.Http.HttpRequestMessage,System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateBadRequestResponse (request As HttpRequestMessage, format As String, ParamArray args As Object()) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateBadRequestResponse : System.Net.Http.HttpRequestMessage * string * obj[] -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateBadRequestResponse (request, format, args)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="format" Type="System.String" />
        <Parameter Name="args" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="request">現在の <see cref="T:System.Net.Http.HttpRequestMessage" /> です。</param>
        <param name="format">複合書式設定文字列。</param>
        <param name="args">0 個以上の書式設定対象オブジェクトを含んだオブジェクト配列。</param>
        <summary>
            作成、<see cref="T:System.Net.Http.HttpResponseMessage" />で、<see cref="F:System.Net.HttpStatusCode.BadRequest" />ステータス コードと<see cref="T:System.Web.Http.HttpError" />HTTP 応答の本文として提供されたメッセージを格納しています。
            </summary>
        <returns>初期化された<see cref="T:System.Net.Http.HttpResponseMessage" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNotFoundResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateNotFoundResponse (this System.Net.Http.HttpRequestMessage request);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateNotFoundResponse(class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateNotFoundResponse(System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateNotFoundResponse (request As HttpRequestMessage) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateNotFoundResponse : System.Net.Http.HttpRequestMessage -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateNotFoundResponse request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
      </Parameters>
      <Docs>
        <param name="request">現在の <see cref="T:System.Net.Http.HttpRequestMessage" /> です。</param>
        <summary>
            作成、<see cref="T:System.Net.Http.HttpResponseMessage" />で、<see cref="F:System.Net.HttpStatusCode.NotFound" />ステータス コードと、既定値<see cref="T:System.Web.Http.HttpError" />として HTTP 応答本文です。
            </summary>
        <returns>初期化された<see cref="T:System.Net.Http.HttpResponseMessage" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNotFoundResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateNotFoundResponse (this System.Net.Http.HttpRequestMessage request, string format, params object[] args);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateNotFoundResponse(class System.Net.Http.HttpRequestMessage request, string format, object[] args) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateNotFoundResponse(System.Net.Http.HttpRequestMessage,System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateNotFoundResponse (request As HttpRequestMessage, format As String, ParamArray args As Object()) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateNotFoundResponse : System.Net.Http.HttpRequestMessage * string * obj[] -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateNotFoundResponse (request, format, args)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="format" Type="System.String" />
        <Parameter Name="args" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="request">現在の <see cref="T:System.Net.Http.HttpRequestMessage" /> です。</param>
        <param name="format">複合書式設定文字列。</param>
        <param name="args">0 個以上の書式設定対象オブジェクトを含んだオブジェクト配列。</param>
        <summary>
            作成、<see cref="T:System.Net.Http.HttpResponseMessage" />で、<see cref="F:System.Net.HttpStatusCode.NotFound" />ステータス コードと<see cref="T:System.Web.Http.HttpError" />HTTP 応答の本文として提供されたメッセージを格納しています。
            </summary>
        <returns>初期化された<see cref="T:System.Net.Http.HttpResponseMessage" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUnauthorizedResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateUnauthorizedResponse (this System.Net.Http.HttpRequestMessage request);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateUnauthorizedResponse(class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateUnauthorizedResponse(System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateUnauthorizedResponse (request As HttpRequestMessage) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateUnauthorizedResponse : System.Net.Http.HttpRequestMessage -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateUnauthorizedResponse request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
      </Parameters>
      <Docs>
        <param name="request">現在の <see cref="T:System.Net.Http.HttpRequestMessage" /> です。</param>
        <summary>
            作成、<see cref="T:System.Net.Http.HttpResponseMessage" />で、<see cref="F:System.Net.HttpStatusCode.Unauthorized" />ステータス コードと、既定値<see cref="T:System.Web.Http.HttpError" />として HTTP 応答本文です。
            </summary>
        <returns>初期化された<see cref="T:System.Net.Http.HttpResponseMessage" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUnauthorizedResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateUnauthorizedResponse (this System.Net.Http.HttpRequestMessage request, string format, params object[] args);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateUnauthorizedResponse(class System.Net.Http.HttpRequestMessage request, string format, object[] args) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateUnauthorizedResponse(System.Net.Http.HttpRequestMessage,System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateUnauthorizedResponse (request As HttpRequestMessage, format As String, ParamArray args As Object()) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateUnauthorizedResponse : System.Net.Http.HttpRequestMessage * string * obj[] -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateUnauthorizedResponse (request, format, args)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="format" Type="System.String" />
        <Parameter Name="args" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="request">現在の <see cref="T:System.Net.Http.HttpRequestMessage" /> です。</param>
        <param name="format">複合書式設定文字列。</param>
        <param name="args">0 個以上の書式設定対象オブジェクトを含んだオブジェクト配列。</param>
        <summary>
            作成、<see cref="T:System.Net.Http.HttpResponseMessage" />で、<see cref="F:System.Net.HttpStatusCode.Unauthorized" />ステータス コードと<see cref="T:System.Web.Http.HttpError" />HTTP 応答の本文として提供されたメッセージを格納しています。
            </summary>
        <returns>初期化された<see cref="T:System.Net.Http.HttpResponseMessage" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHeaderOrDefault">
      <MemberSignature Language="C#" Value="public static string GetHeaderOrDefault (this System.Net.Http.HttpRequestMessage request, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetHeaderOrDefault(class System.Net.Http.HttpRequestMessage request, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.GetHeaderOrDefault(System.Net.Http.HttpRequestMessage,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetHeaderOrDefault (request As HttpRequestMessage, name As String) As String" />
      <MemberSignature Language="F#" Value="static member GetHeaderOrDefault : System.Net.Http.HttpRequestMessage * string -&gt; string" Usage="System.Net.Http.HttpRequestMessageExtensions.GetHeaderOrDefault (request, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="request">ヘッダーを検索する場所の要求。</param>
        <param name="name">ヘッダーの名前。</param>
        <summary>
            単一の値としては、最初の HTTP ヘッダー値を取得または<c>null</c>存在していない場合。
            </summary>
        <returns>最初の HTTP ヘッダーの値または<c>null</c>存在していない場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsIfNoneMatch">
      <MemberSignature Language="C#" Value="public static bool IsIfNoneMatch (this System.Net.Http.HttpRequestMessage request, System.Net.Http.Headers.EntityTagHeaderValue current);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsIfNoneMatch(class System.Net.Http.HttpRequestMessage request, class System.Net.Http.Headers.EntityTagHeaderValue current) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.IsIfNoneMatch(System.Net.Http.HttpRequestMessage,System.Net.Http.Headers.EntityTagHeaderValue)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IsIfNoneMatch (request As HttpRequestMessage, current As EntityTagHeaderValue) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsIfNoneMatch : System.Net.Http.HttpRequestMessage * System.Net.Http.Headers.EntityTagHeaderValue -&gt; bool" Usage="System.Net.Http.HttpRequestMessageExtensions.IsIfNoneMatch (request, current)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="current" Type="System.Net.Http.Headers.EntityTagHeaderValue" />
      </Parameters>
      <Docs>
        <param name="request">一致するように要求します。</param>
        <param name="current">リソースの現在の etag。 (つまり、リソースがまだ存在しない) 現在の etag がない場合を使用して<c>null</c>です。</param>
        <summary>
            要求の条件付きのことを確認、<c>なし-If-match</c> HTTP ヘッダー フィールドに一致する値を持つ、<paramref name="current" />値。 場合、 <c>true</c> 304 (変更なし) または 412 (Precondition Failed) のステータス コードを使用することを示すためにこれを使用することができます。
            </summary>
        <returns>返します<c>true</c>場合の<c>なし-If-match</c>値です。 現在の etag 値と一致または<c>なし-If-match</c>値は"*"と<paramref name="current" />は null。 それ以外の場合は false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>