<Type Name="EnumerationMode" FullName="Microsoft.ServiceFabric.Data.Collections.EnumerationMode">
  <TypeSignature Language="C#" Value="public enum EnumerationMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed EnumerationMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.EnumerationMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum EnumerationMode" />
  <TypeSignature Language="F#" Value="type EnumerationMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="adfeb-101">信頼性の高いコレクションの列挙体の順序なしまたは順序付けする必要がある時に項目が返された場合を指定します。</span><span class="sxs-lookup"><span data-stu-id="adfeb-101">Specifies if items returned during enumeration of reliable collections should be unordered or ordered.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Ordered">
      <MemberSignature Language="C#" Value="Ordered" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Data.Collections.EnumerationMode Ordered = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Data.Collections.EnumerationMode.Ordered" />
      <MemberSignature Language="VB.NET" Value="Ordered" />
      <MemberSignature Language="F#" Value="Ordered = 1" Usage="Microsoft.ServiceFabric.Data.Collections.EnumerationMode.Ordered" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.Collections.EnumerationMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="adfeb-102">結果は、順序付けされた列挙型として返されます。</span><span class="sxs-lookup"><span data-stu-id="adfeb-102">Results are be returned as an ordered enumeration.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unordered">
      <MemberSignature Language="C#" Value="Unordered" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Data.Collections.EnumerationMode Unordered = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Data.Collections.EnumerationMode.Unordered" />
      <MemberSignature Language="VB.NET" Value="Unordered" />
      <MemberSignature Language="F#" Value="Unordered = 0" Usage="Microsoft.ServiceFabric.Data.Collections.EnumerationMode.Unordered" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.Collections.EnumerationMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="adfeb-103">結果は、順序付けられていない列挙型として返されます。</span><span class="sxs-lookup"><span data-stu-id="adfeb-103">Results are returned as an unordered enumeration.</span></span> <span data-ttu-id="adfeb-104">最も高速の列挙モードです。</span><span class="sxs-lookup"><span data-stu-id="adfeb-104">Fastest enumeration mode.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>