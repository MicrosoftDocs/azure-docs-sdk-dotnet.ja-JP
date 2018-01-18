<Type Name="GraphSONMode" FullName="Microsoft.Azure.Graphs.GraphSONMode">
  <TypeSignature Language="C#" Value="public enum GraphSONMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed GraphSONMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Graphs.GraphSONMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum GraphSONMode" />
  <TypeSignature Language="F#" Value="type GraphSONMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
    <AssemblyVersion>1.14.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="722ba-101">Gremlin クエリから結果の出力形式を定義します。</span><span class="sxs-lookup"><span data-stu-id="722ba-101">Defines the output formats for results from gremlin queries.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Compact">
      <MemberSignature Language="C#" Value="Compact" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphSONMode Compact = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphSONMode.Compact" />
      <MemberSignature Language="VB.NET" Value="Compact" />
      <MemberSignature Language="F#" Value="Compact = 0" Usage="Microsoft.Azure.Graphs.GraphSONMode.Compact" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphSONMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="722ba-102">出力を GraphSON コンパクトな形式を使用します。</span><span class="sxs-lookup"><span data-stu-id="722ba-102">Use the GraphSON compact format for outputs.</span></span>
            <span data-ttu-id="722ba-103">出力では、有効な GraphSON を隣接性情報を含めずに返します。</span><span class="sxs-lookup"><span data-stu-id="722ba-103">Output will return valid GraphSON, without including adjacency information.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Normal">
      <MemberSignature Language="C#" Value="Normal" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphSONMode Normal = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphSONMode.Normal" />
      <MemberSignature Language="VB.NET" Value="Normal" />
      <MemberSignature Language="F#" Value="Normal = 1" Usage="Microsoft.Azure.Graphs.GraphSONMode.Normal" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphSONMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="722ba-104">通常の GraphSON 形式の使用を出力します。</span><span class="sxs-lookup"><span data-stu-id="722ba-104">Use normal GraphSON format for outputs.</span></span>
            <span data-ttu-id="722ba-105">出力には、有効な GraphSON、ナチュラル情報などが返されます。</span><span class="sxs-lookup"><span data-stu-id="722ba-105">Output will return valid GraphSON, including adjacency information.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>