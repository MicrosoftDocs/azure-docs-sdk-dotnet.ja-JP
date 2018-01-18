<Type Name="IServiceRemotingRequestMessageHeader" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingRequestMessageHeader" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingRequestMessageHeader" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingRequestMessageHeader" />
  <TypeSignature Language="F#" Value="type IServiceRemotingRequestMessageHeader = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3057c-101">ServiceRemoting メッセージと共に送信されるヘッダーを指定します。</span><span class="sxs-lookup"><span data-stu-id="3057c-101">Specifies the headers that are sent along with a ServiceRemoting message.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddHeader">
      <MemberSignature Language="C#" Value="public void AddHeader (string headerName, byte[] headerValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AddHeader(string headerName, unsigned int8[] headerValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader.AddHeader(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddHeader (headerName As String, headerValue As Byte())" />
      <MemberSignature Language="F#" Value="abstract member AddHeader : string * byte[] -&gt; unit" Usage="iServiceRemotingRequestMessageHeader.AddHeader (headerName, headerValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="headerName" Type="System.String" />
        <Parameter Name="headerValue" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="headerName"><span data-ttu-id="3057c-102">ヘッダー名。</span><span class="sxs-lookup"><span data-stu-id="3057c-102">The header Name.</span></span></param>
        <param name="headerValue"><span data-ttu-id="3057c-103">ヘッダーの値。</span><span class="sxs-lookup"><span data-stu-id="3057c-103">The header value.</span></span></param>
        <summary>
            <span data-ttu-id="3057c-104">指定した名前と値を持つ新しいヘッダーを追加します。</span><span class="sxs-lookup"><span data-stu-id="3057c-104">Adds a new header with the specified name and value.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InterfaceId">
      <MemberSignature Language="C#" Value="public int InterfaceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 InterfaceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader.InterfaceId" />
      <MemberSignature Language="VB.NET" Value="Public Property InterfaceId As Integer" />
      <MemberSignature Language="F#" Value="member this.InterfaceId : int with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader.InterfaceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3057c-105">取得またはリモートのインターフェイスのインターフェイス id を設定します。</span><span class="sxs-lookup"><span data-stu-id="3057c-105">Gets or sets the interface id of the remote interface.</span></span>
            </summary>
        <value><span data-ttu-id="3057c-106">インターフェイス id です。</span><span class="sxs-lookup"><span data-stu-id="3057c-106">The interface id.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvocationId">
      <MemberSignature Language="C#" Value="public string InvocationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InvocationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader.InvocationId" />
      <MemberSignature Language="VB.NET" Value="Public Property InvocationId As String" />
      <MemberSignature Language="F#" Value="member this.InvocationId : string with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader.InvocationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="InvocationId", Order=3)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3057c-107">取得またはリモート メソッド呼び出しの識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="3057c-107">Gets or sets the identifier for the remote method invocation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MethodId">
      <MemberSignature Language="C#" Value="public int MethodId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MethodId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader.MethodId" />
      <MemberSignature Language="VB.NET" Value="Public Property MethodId As Integer" />
      <MemberSignature Language="F#" Value="member this.MethodId : int with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader.MethodId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3057c-108">取得またはリモート メソッドのメソッド Id を設定します。</span><span class="sxs-lookup"><span data-stu-id="3057c-108">Gets or sets the methodId of the remote method.</span></span>
            </summary>
        <value><span data-ttu-id="3057c-109">メソッド ID。</span><span class="sxs-lookup"><span data-stu-id="3057c-109">The method id.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetHeaderValue">
      <MemberSignature Language="C#" Value="public bool TryGetHeaderValue (string headerName, out byte[] headerValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryGetHeaderValue(string headerName, [out] unsigned int8[]&amp; headerValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader.TryGetHeaderValue(System.String,System.Byte[]@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetHeaderValue (headerName As String, ByRef headerValue As Byte()) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryGetHeaderValue : string *  -&gt; bool" Usage="iServiceRemotingRequestMessageHeader.TryGetHeaderValue (headerName, headerValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="headerName" Type="System.String" />
        <Parameter Name="headerValue" Type="System.Byte[]&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="headerName"><span data-ttu-id="3057c-110">ヘッダー名。</span><span class="sxs-lookup"><span data-stu-id="3057c-110">The header Name.</span></span></param>
        <param name="headerValue"><span data-ttu-id="3057c-111">ヘッダーの値。</span><span class="sxs-lookup"><span data-stu-id="3057c-111">The header value.</span></span></param>
        <summary>
            <span data-ttu-id="3057c-112">指定した名前のヘッダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="3057c-112">Gets the header with the specified name.</span></span>
            </summary>
        <returns><span data-ttu-id="3057c-113">その名前を持つヘッダーが存在する場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="3057c-113">true if a header with that name exists; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>