<Type Name="GeometryOperationExtensions" FullName="Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions">
  <TypeSignature Language="C#" Value="public static class GeometryOperationExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit GeometryOperationExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module GeometryOperationExtensions" />
  <TypeSignature Language="F#" Value="type GeometryOperationExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            サポートされる操作<see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />Azure Cosmos DB サービスの種類。 これらの操作は LINQ 式のみで使用されるされ、サーバーで評価されます。 クライアント ライブラリで提供される実装はありません。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Distance">
      <MemberSignature Language="C#" Value="public static double Distance (this Microsoft.Azure.Documents.Spatial.Geometry from, Microsoft.Azure.Documents.Spatial.Geometry to);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig float64 Distance(class Microsoft.Azure.Documents.Spatial.Geometry from, class Microsoft.Azure.Documents.Spatial.Geometry to) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.Distance(Microsoft.Azure.Documents.Spatial.Geometry,Microsoft.Azure.Documents.Spatial.Geometry)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Distance (from As Geometry, to As Geometry) As Double" />
      <MemberSignature Language="F#" Value="static member Distance : Microsoft.Azure.Documents.Spatial.Geometry * Microsoft.Azure.Documents.Spatial.Geometry -&gt; double" Usage="Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.Distance (from, to)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="Microsoft.Azure.Documents.Spatial.Geometry" RefType="this" />
        <Parameter Name="to" Type="Microsoft.Azure.Documents.Spatial.Geometry" />
      </Parameters>
      <Docs>
        <param name="from">最初<see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />です。</param>
        <param name="to">2 番目<see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />です。</param>
        <summary>
            Azure Cosmos DB サービスの 2 つのジオメトリ間メートル単位で距離です。
            </summary>
        <returns>メートル単位で 2 つのジオメトリの間の距離を返します。</returns>
        <remarks>
            この関数がのジオメトリのみをサポートする今日<see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" />型です。
            </remarks>
        <example>
          <code><![CDATA[
            var distanceQuery = documents.Where(document => document.Location.Distance(new Point(20.1, 20)) < 20000);
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="Intersects">
      <MemberSignature Language="C#" Value="public static bool Intersects (this Microsoft.Azure.Documents.Spatial.Geometry geometry1, Microsoft.Azure.Documents.Spatial.Geometry geometry2);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Intersects(class Microsoft.Azure.Documents.Spatial.Geometry geometry1, class Microsoft.Azure.Documents.Spatial.Geometry geometry2) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.Intersects(Microsoft.Azure.Documents.Spatial.Geometry,Microsoft.Azure.Documents.Spatial.Geometry)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Intersects (geometry1 As Geometry, geometry2 As Geometry) As Boolean" />
      <MemberSignature Language="F#" Value="static member Intersects : Microsoft.Azure.Documents.Spatial.Geometry * Microsoft.Azure.Documents.Spatial.Geometry -&gt; bool" Usage="Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.Intersects (geometry1, geometry2)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="geometry1" Type="Microsoft.Azure.Documents.Spatial.Geometry" RefType="this" />
        <Parameter Name="geometry2" Type="Microsoft.Azure.Documents.Spatial.Geometry" />
      </Parameters>
      <Docs>
        <param name="geometry1">最初<see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />です。</param>
        <param name="geometry2">2 番目<see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />です。</param>
        <summary>
            Geometry1 が geometry2 と交差するかどうかを確認します。
            </summary>
        <returns>True geometry2、geometry1 と交差するそれ以外の場合は false を返しますを返します。</returns>
        <remarks>To be added.</remarks>
        <example>
          <code><![CDATA[
            var distanceQuery = documents.Where(document => document.Location.Intersects(new Point(20.1, 20)));
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="IsValid">
      <MemberSignature Language="C#" Value="public static bool IsValid (this Microsoft.Azure.Documents.Spatial.Geometry geometry);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsValid(class Microsoft.Azure.Documents.Spatial.Geometry geometry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.IsValid(Microsoft.Azure.Documents.Spatial.Geometry)" />
      <MemberSignature Language="F#" Value="static member IsValid : Microsoft.Azure.Documents.Spatial.Geometry -&gt; bool" Usage="Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.IsValid geometry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="geometry" Type="Microsoft.Azure.Documents.Spatial.Geometry" RefType="this" />
      </Parameters>
      <Docs>
        <param name="geometry">有効性を確認するジオメトリ。</param>
        <summary>
          <para>
            かどうかを<paramref name="geometry" />が有効では指定され、Azure Cosmos DB サービスによってインデックス付きで使用されるクエリを指定できます。
            </para>
          <para>
            Geometry が有効でない場合にいないインデックスが作成されます。 またクエリ時に無効なジオメトリに相当する<c>未定義</c>です。
            </para>
        </summary>
        <returns>
          <c>true</c>形状は無効な場合です。 <c>false</c>それ以外の場合。</returns>
        <remarks>
            この関数では、現在<paramref name="geometry" />型の<see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" />と<see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Polygon" />です。
            </remarks>
        <example>
          <para>
            この例では、インデックスが作成されなかったが無効なジオメトリを含むすべてのドキュメントを選択します。
            </para>
          <code><![CDATA[
            var invalidDocuments = documents.Where(document => !document.Location.IsValid());
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="IsValidDetailed">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Spatial.GeometryValidationResult IsValidDetailed (this Microsoft.Azure.Documents.Spatial.Geometry geometry);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.Spatial.GeometryValidationResult IsValidDetailed(class Microsoft.Azure.Documents.Spatial.Geometry geometry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.IsValidDetailed(Microsoft.Azure.Documents.Spatial.Geometry)" />
      <MemberSignature Language="F#" Value="static member IsValidDetailed : Microsoft.Azure.Documents.Spatial.Geometry -&gt; Microsoft.Azure.Documents.Spatial.GeometryValidationResult" Usage="Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.IsValidDetailed geometry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Spatial.GeometryValidationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="geometry" Type="Microsoft.Azure.Documents.Spatial.Geometry" RefType="this" />
      </Parameters>
      <Docs>
        <param name="geometry">有効性を確認するジオメトリ。</param>
        <summary>
          <para>
            かどうかを<paramref name="geometry" />が有効では指定され、Azure Cosmos DB サービスによってインデックス付きで使用されるクエリを指定できます。
            </para>
          <para>
            Geometry が有効でない場合にいないインデックスが作成されます。 またクエリ時に無効なジオメトリに相当する<c>未定義</c>です。
            </para>
        </summary>
        <returns>インスタンス<see cref="T:Microsoft.Azure.Documents.Spatial.GeometryValidationResult" />です。</returns>
        <remarks>
            この関数では、現在<paramref name="geometry" />型の<see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" />と<see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Polygon" />です。
            </remarks>
        <example>
          <para>
            この例では、インデックスが作成されなかったが無効なジオメトリを含むすべてのドキュメントを選択します。
            </para>
          <code><![CDATA[
            var invalidReason = documents.Where(document => !document.Location.IsValid()).Select(document => document.Location.IsValidDetailed());
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="Within">
      <MemberSignature Language="C#" Value="public static bool Within (this Microsoft.Azure.Documents.Spatial.Geometry inner, Microsoft.Azure.Documents.Spatial.Geometry outer);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Within(class Microsoft.Azure.Documents.Spatial.Geometry inner, class Microsoft.Azure.Documents.Spatial.Geometry outer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.Within(Microsoft.Azure.Documents.Spatial.Geometry,Microsoft.Azure.Documents.Spatial.Geometry)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Within (inner As Geometry, outer As Geometry) As Boolean" />
      <MemberSignature Language="F#" Value="static member Within : Microsoft.Azure.Documents.Spatial.Geometry * Microsoft.Azure.Documents.Spatial.Geometry -&gt; bool" Usage="Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.Within (inner, outer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inner" Type="Microsoft.Azure.Documents.Spatial.Geometry" RefType="this" />
        <Parameter Name="outer" Type="Microsoft.Azure.Documents.Spatial.Geometry" />
      </Parameters>
      <Docs>
        <param name="inner">内部<see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />です。</param>
        <param name="outer">外部<see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />です。</param>
        <summary>
            かどうかを<paramref name="inner" /><see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />完全に含まれている<paramref name="outer" /> <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> Cosmos DB の Azure サービスにします。
            </summary>
        <returns>
          <c>true</c>場合<paramref name="inner" /><see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />完全に含まれている<paramref name="outer" /><see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />です。
            <c>false</c>それ以外の場合。
            </returns>
        <remarks>
            この関数では、現在<paramref name="inner" />型の geometry<see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" />と型の外部のジオメトリ<see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Polygon" />です。
            </remarks>
        <example>
          <code><![CDATA[
            Polygon polygon = new Polygon(
                   new[]
                   {
                        new Position(10, 10),
                        new Position(30, 10),
                        new Position(30, 30),
                        new Position(10, 30),
                        new Position(10, 10)
                   });
            var withinQuery = documents.Where(document => document.Location.Within(polygon));
            ]]></code>
        </example>
      </Docs>
    </Member>
  </Members>
</Type>