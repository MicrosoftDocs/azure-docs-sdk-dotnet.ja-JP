<Type Name="TableContractResolver" FullName="Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver">
  <TypeSignature Language="C#" Value="public class TableContractResolver : Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableContractResolver extends Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver" />
  <TypeSignature Language="VB.NET" Value="Public Class TableContractResolver&#xA;Inherits ServiceContractResolver" />
  <TypeSignature Language="F#" Value="type TableContractResolver = class&#xA;    inherit ServiceContractResolver" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="33a8b-101">このクラスは、実装、<see cref="T:Newtonsoft.Json.Serialization.IContractResolver" />の逆シリアル化のサポートを提供する、 <see cref="T:System.Web.Http.OData.Delta`1" /> JSON.NET を使用して入力します。</span><span class="sxs-lookup"><span data-stu-id="33a8b-101">This class implements an <see cref="T:Newtonsoft.Json.Serialization.IContractResolver" /> to provide support for deserialization of the <see cref="T:System.Web.Http.OData.Delta`1" /> type using JSON.NET.</span></span> 
            </summary>
    <remarks>
            <span data-ttu-id="33a8b-102">用に作成されたコントラクト<see cref="T:System.Web.Http.OData.Delta`1" />型および基になる型のプロパティ名を使用してプロパティを逆シリアル化します。</span><span class="sxs-lookup"><span data-stu-id="33a8b-102">The contract created for <see cref="T:System.Web.Http.OData.Delta`1" /> will deserialize properties using the types and property names of the underlying type.</span></span> <span data-ttu-id="33a8b-103"><see cref="T:Newtonsoft.Json.Serialization.JsonProperty" />インスタンスが、基になる型からコピーされた<see cref="T:Newtonsoft.Json.Serialization.JsonContract" />動的オブジェクトを使用するカスタマイズされたとします。</span><span class="sxs-lookup"><span data-stu-id="33a8b-103">The <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" /> instances are copied from the underlying type's <see cref="T:Newtonsoft.Json.Serialization.JsonContract" /> and customized to work with a dynamic object.</span></span> <span data-ttu-id="33a8b-104">特に、カスタム<see cref="T:Newtonsoft.Json.Serialization.IValueProvider" />取得およびのコントラクトを使用して値を設定するために使用<see cref="T:System.Dynamic.DynamicObject" />、どの<see cref="T:System.Web.Http.OData.Delta`1" />から継承します。</span><span class="sxs-lookup"><span data-stu-id="33a8b-104">In particular, a custom <see cref="T:Newtonsoft.Json.Serialization.IValueProvider" /> is used to get and set values using the contract of <see cref="T:System.Dynamic.DynamicObject" />, which <see cref="T:System.Web.Http.OData.Delta`1" /> inherits from.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableContractResolver (System.Net.Http.Formatting.MediaTypeFormatter formatter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.Formatting.MediaTypeFormatter formatter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver.#ctor(System.Net.Http.Formatting.MediaTypeFormatter)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (formatter As MediaTypeFormatter)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver : System.Net.Http.Formatting.MediaTypeFormatter -&gt; Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver" Usage="new Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver formatter" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="formatter" Type="System.Net.Http.Formatting.MediaTypeFormatter" />
      </Parameters>
      <Docs>
        <param name="formatter"><span data-ttu-id="33a8b-105"><see cref="T:System.Net.Http.Formatting.MediaTypeFormatter" />この<see cref="T:Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver" />に関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="33a8b-105">The <see cref="T:System.Net.Http.Formatting.MediaTypeFormatter" /> that this <see cref="T:Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver" /> is associated with.</span></span></param>
        <summary>
            <span data-ttu-id="33a8b-106">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver" />クラスに、指定された<paramref name="formatter" />です。</span><span class="sxs-lookup"><span data-stu-id="33a8b-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver" /> class with a given <paramref name="formatter" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateContract">
      <MemberSignature Language="C#" Value="protected override Newtonsoft.Json.Serialization.JsonContract CreateContract (Type objectType);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Newtonsoft.Json.Serialization.JsonContract CreateContract(class System.Type objectType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver.CreateContract(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateContract (objectType As Type) As JsonContract" />
      <MemberSignature Language="F#" Value="override this.CreateContract : Type -&gt; Newtonsoft.Json.Serialization.JsonContract" Usage="tableContractResolver.CreateContract objectType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.Serialization.JsonContract</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="objectType"><span data-ttu-id="33a8b-107">コントラクトを取得する型。</span><span class="sxs-lookup"><span data-stu-id="33a8b-107">The type to get the contract for.</span></span></param>
        <summary>
            <span data-ttu-id="33a8b-108">指定された型のコントラクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="33a8b-108">Gets the contract for a given type.</span></span> <span data-ttu-id="33a8b-109">型<see cref="T:System.Web.Http.OData.Delta`1" />は、その他のすべての型が基本クラスによって処理される一方に特別に扱われます。</span><span class="sxs-lookup"><span data-stu-id="33a8b-109">The type <see cref="T:System.Web.Http.OData.Delta`1" /> is treated specially whereas all other types are handled by the base class.</span></span> 
            </summary>
        <returns><span data-ttu-id="33a8b-110">A<see cref="T:Newtonsoft.Json.Serialization.JsonContract" />特定の型にします。</span><span class="sxs-lookup"><span data-stu-id="33a8b-110">A <see cref="T:Newtonsoft.Json.Serialization.JsonContract" /> for the given type.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeltaContract">
      <MemberSignature Language="C#" Value="protected virtual Newtonsoft.Json.Serialization.JsonContract GetDeltaContract (Type objectType);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Newtonsoft.Json.Serialization.JsonContract GetDeltaContract(class System.Type objectType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Serialization.TableContractResolver.GetDeltaContract(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function GetDeltaContract (objectType As Type) As JsonContract" />
      <MemberSignature Language="F#" Value="abstract member GetDeltaContract : Type -&gt; Newtonsoft.Json.Serialization.JsonContract&#xA;override this.GetDeltaContract : Type -&gt; Newtonsoft.Json.Serialization.JsonContract" Usage="tableContractResolver.GetDeltaContract objectType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.Serialization.JsonContract</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="objectType"><span data-ttu-id="33a8b-111">コントラクトを提供する型。</span><span class="sxs-lookup"><span data-stu-id="33a8b-111">The type to provide a contract for.</span></span></param>
        <summary>
            <span data-ttu-id="33a8b-112">型のコントラクトを作成<see cref="T:System.Web.Http.OData.Delta`1" />です。</span><span class="sxs-lookup"><span data-stu-id="33a8b-112">Creates a contract for a type of <see cref="T:System.Web.Http.OData.Delta`1" />.</span></span>
            </summary>
        <returns><span data-ttu-id="33a8b-113">A<see cref="T:Newtonsoft.Json.Serialization.JsonContract" />特定の型にします。</span><span class="sxs-lookup"><span data-stu-id="33a8b-113">A <see cref="T:Newtonsoft.Json.Serialization.JsonContract" /> for the given type.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>