<Type Name="TokenProvider+Key" FullName="Microsoft.ServiceBus.TokenProvider+Key">
  <TypeSignature Language="C#" Value="protected internal class TokenProvider.Key : IEquatable&lt;Microsoft.ServiceBus.TokenProvider.Key&gt;" />
  <TypeSignature Language="ILAsm" Value=".class nested protected auto ansi beforefieldinit TokenProvider/Key extends System.Object implements class System.IEquatable`1&lt;class Microsoft.ServiceBus.TokenProvider/Key&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.TokenProvider.Key" />
  <TypeSignature Language="VB.NET" Value="Protected Friend Class TokenProvider.Key&#xA;Implements IEquatable(Of TokenProvider.Key)" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.ServiceBus.TokenProvider+Key&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Key (string appliesTo, string claim);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string appliesTo, string claim) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.Key.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (appliesTo As String, claim As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.TokenProvider.Key : string * string -&gt; Microsoft.ServiceBus.TokenProvider.Key" Usage="new Microsoft.ServiceBus.TokenProvider.Key (appliesTo, claim)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="claim" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appliesTo"><span data-ttu-id="bd51e-101">キーが対象アドレスを指定します。</span><span class="sxs-lookup"><span data-stu-id="bd51e-101">Specifies the address where the key applies to.</span></span></param>
        <param name="claim"><span data-ttu-id="bd51e-102">特定のユーザー、アプリケーション、コンピューター、またはその他のエンティティを指定します</span><span class="sxs-lookup"><span data-stu-id="bd51e-102">Specifies a specific user, application, computer, or other entity</span></span></param>
        <summary><span data-ttu-id="bd51e-103"><see cref="T:Microsoft.ServiceBus.TokenProvider.Key" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bd51e-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.TokenProvider.Key" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.ServiceBus.TokenProvider.Key other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.ServiceBus.TokenProvider/Key other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.Key.Equals(Microsoft.ServiceBus.TokenProvider.Key)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As TokenProvider.Key) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.ServiceBus.TokenProvider.Key -&gt; bool" Usage="key.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.ServiceBus.TokenProvider+Key" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="bd51e-104">現在のオブジェクトと比較するキー。</span><span class="sxs-lookup"><span data-stu-id="bd51e-104">The key to compare with the current object.</span></span></param>
        <summary><span data-ttu-id="bd51e-105">指定したキーが現在のオブジェクトと等しいかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="bd51e-105">Determines whether the specified key is equal to the current object.</span></span></summary>
        <returns><span data-ttu-id="bd51e-106">指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="bd51e-106">true if the specified object is equal to the current object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.Key.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="key.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="bd51e-107">現在のオブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bd51e-107">The object to compare with the current object.</span></span></param>
        <summary><span data-ttu-id="bd51e-108">指定したオブジェクトが、現在のオブジェクトと等しいかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="bd51e-108">Determines whether the specified object is equal to the current object.</span></span></summary>
        <returns><span data-ttu-id="bd51e-109">指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="bd51e-109">true if the specified object is equal to the current object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.Key.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="key.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="bd51e-110">キーのハッシュ コードを返します。</span><span class="sxs-lookup"><span data-stu-id="bd51e-110">Returns the hash code for the key.</span></span></summary>
        <returns><span data-ttu-id="bd51e-111">キーのハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="bd51e-111">The hash code for the key.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>